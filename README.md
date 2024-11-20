# cde-identification
Automate the extraction and identification of CDEs from trade data source systems - Deploy NLP models &amp; LLMs to scan metadata and field definitions to identify CDEs across systems

Sample trade data - https://www.finra.org/filing-reporting/trace/content-licensing/end-day-file-layout-and-agreement

MTRS Debt Securities Transaction Reporting - https://www.iiroc.ca/media/12126/download?inline 

Steps - for a given financial regulation

a) Analyze the original regulatory text, identify, and summarize the data required for reporting, define data elements 
   Prompt: Analyze this MTRS regulatory text, identify, and summarize the data required for reporting, define data elements. Give me a simple list with one line definition, make sure to include the all data elements for debt securities

b) Given a trade dataset in a bank, come up with a data dictionary – standardized names (possibly aligning to standard such as ISDA CDM or FpML) and definition. 

c) Match the regulatory data requirement with the data dictionary and provide a detailed analysis of useful data, gaps, risks etc.

