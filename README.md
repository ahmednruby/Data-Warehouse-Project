# Data-Warehouse-Project
Data Architecture
1. Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
   
Project Overview
This project is about building a complete data solution from raw data to final reports.  
It includes the following main stages:
1. Data Architecture – Designing a modern data warehouse using the Medallion Architecture with three layers:
   - Bronze (raw data)
   - Silver (cleaned and structured data)
   - Gold (ready for analysis)

2. ETL Pipelines – Extracting data from source systems, transforming it, and loading it into the data warehouse.

3. Data Modeling – Creating fact and dimension tables to support efficient data analysis.

4. Analytics & Reporting – Building reports using SQL to gain insights from the data.
