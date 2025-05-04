# 🗂️ Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository!
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

# 🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

![data_architecture](https://github.com/user-attachments/assets/2e6f35b7-3041-4ce2-9b51-45bd69b0a270)

1. Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

# 📖 Project Overview
This project involves:

1. Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
2. ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
3. Data Modeling: Developing fact and dimension tables optimized for analytical queries.
4. Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

# 📌 This project encompasses the following key areas of expertise:

1. SQL Development
2. Data Architect
3. Data Engineering
4. ETL Pipeline Developer
5. Data Modeling
6. Data Analytics

# 📌 Project Requirements
# Building the Data Warehouse (Data Engineering)
## Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

## Specifications
1. Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
3. Data Quality: Cleanse and resolve data quality issues prior to analysis.
3. Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
4. Scope: Focus on the latest dataset only; historization of data is not required.
5. Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

# 📌 BI: Analytics & Reporting (Data Analysis)
## Objective
Develop SQL-based analytics to deliver detailed insights into:

1. Customer Behavior
2. Product Performance
3. Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.

# 📂 Repository Structure

![image](https://github.com/user-attachments/assets/a66d879a-65ce-4c77-abe0-422223311179)

# 🪙 License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.
