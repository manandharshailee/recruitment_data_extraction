PDF Data Extraction 
Overview
This project builds a Python-based workflow to extract structured data from PDF reports and merge it with external labor market data (BLS). The goal is to construct an analysis-ready dataset for studying the impact of free community college policies on military enlistment and unemployment outcomes.
The pipeline includes data extraction, cleaning, validation checks, and dataset integration to ensure consistency and reproducibility across sources.


Workflow
PDF Data Extraction (extract_tables.ipynb): Extracts, cleans, and validates accession data from PDF reports
BLS Data Processing (bls_unemp_data.ipynb): Downloads and processes unemployment data from BLS
Merging & Analysis Dataset Construction (merge_accessions_unemp.ipynb): Combines datasets into a unified panel for analysis
