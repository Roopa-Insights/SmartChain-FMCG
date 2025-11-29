# Automated AI driven FMCG supply chain analytics pipeline
Ingest order emails, clean and enrich data with Quadratic generated Python, orchestrate ETL with n8n, store normalized tables in Supabase Postgres, compute OTIF and fill rate KPIs, quantify revenue loss from undelivered orders, and deliver automated reports.

## Problem statement
FMCG teams need an automated, reproducible pipeline to turn emailed order data into reliable KPIs and prioritized operational actions. Manual processing causes delays, inconsistent metrics, and unquantified revenue loss from undelivered orders.

## Dataset
<a href="https://github.com/Roopa-Insights/SmartChain-FMCG/blob/main/Dataset.zip"> Dataset used</a>

## What it does
- Ingests order emails and attachments from Gmail using Google Cloud OAuth.
- Orchestrates parsing, validation, and automation with n8n.
- Uses Quadratic AI prompts to generate Python for cleaning, merging, and exchange rate enrichment.
- Produces a canonical fact_summary table and KPI outputs using pandas.
- Stores raw and cleaned tables in Supabase Postgres.
- Automates scheduled reports and alerts via n8n.
- 
## Core outputs
- KPI outputs: Total Order Lines, Line Fill Rate, Volume Fill Rate, Total Orders, On Time %, In Full %, OTIF %.
- Business analyses: estimated revenue loss from unshipped quantities, customers with OTIF discrepancies, categories with low In Full rates, average delivery delay statistics.

##  related images and large files
- Workflow diagrams and screenshots: <a href="https://github.com/Roopa-Insights/SmartChain-FMCG/blob/main/My%20workflow.png"> </a> 
- n8n screenshots: <a href="https://github.com/Roopa-Insights/SmartChain-FMCG/blob/main/Postgre_data_ingestion.png"> </a>
- Quadratic sheet : <a href="https://github.com/Roopa-Insights/SmartChain-FMCG/blob/main/Date%20Table.xlsx"></a>

## Conclusion
Compute the KPIs from fact_summary to quantify operational gaps. Focus first on OTIF and revenue loss from unshipped quantities: OTIF synthesizes the customer experience, while revenue loss quantifies business impact.
Next steps

