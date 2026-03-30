Data Warehouse Project – Portfolio Version
📌 Project Overview

This project demonstrates a Data Warehouse built using layered architecture (Bronze → Silver → Gold → Diamond) to transform raw data into business-ready insights.
It simulates a retail business scenario, consolidating multiple data sources to support sales, marketing, and operational analytics.

📌 Tech Stack
Database / Data Storage:  MySQL
ETL / Data Processing:  SQL 
Visualization (optional): Power BI 
Other tools: GitHub for version control

📌Data Diagram 
<img width="1153" height="731" alt="Screenshot 2026-03-30 142814" src="https://github.com/user-attachments/assets/1552763c-37a4-486c-bcf1-f3463e1c2564" />

📌Relationships across the tables
<img width="942" height="595" alt="Screenshot 2026-03-30 142840" src="https://github.com/user-attachments/assets/403bfee6-d015-4ee0-a875-7115c2b05d59" />


📌Layer Descriptions:

Raw / Source Data: Original unprocessed data from multiple sources.
Bronze Layer: Cleansed, validated raw data.
Silver Layer: Structured and enriched for analytics.
Gold Layer: Business-ready tables for reporting.
Diamond Layer: Aggregated insights for dashboards / KPIs.

📌 Data Pipeline
Data Ingestion: Load raw CSV / JSON / database files into the Bronze layer.
Data Cleaning & Transformation: Remove duplicates, handle missing values, normalize formats.
Data Modeling: Structure tables in Silver layer for efficient analytics queries.
Aggregation & Reporting: Create Gold tables for dashboards and decision-making.
Insights Extraction: Diamond layer for KPIs and visual analytics.
