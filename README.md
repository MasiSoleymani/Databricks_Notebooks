**Databricks_Notebooks**
Notebooks showcasing my hands-on experience with Databricks, Delta Lake, PySpark transformations, CI/CD integration, and data pipeline automation using Azure.


**Overview**
Designed and implemented a complete ETL workflow in Databricks leveraging the Bronze–Silver–Gold layered architecture to process and prepare datasets for advanced analytics. The pipeline ingests raw data, applies structured transformations, and produces curated datasets ready for visualization and reporting.


**Architecture & Workflow**
1.	Bronze Layer – Raw Data Ingestion
o	Automated ingestion using Databricks Autoloader to handle new files efficiently.
o	Parameter-driven job configuration for flexible deployments.
2.	Silver Layer – Data Cleansing & Standardization
o	Applied transformations and quality checks using PySpark and Spark SQL.
o	Created clean, structured datasets for customers, orders, and products.
3.	Gold Layer – Analytics-Ready Data
o	Built aggregated and joined tables for business intelligence and reporting.
o	Final fact and dimension tables support KPI dashboards and ad-hoc queries.


**Tools & Technologies**
•	Pipeline Orchestration: Databricks Jobs, Delta Live Tables (DLT)
•	Data Transformation: PySpark, Spark SQL
•	Data Modeling: Bronze–Silver–Gold layered design
•	Optimization: Job clusters for scalable processing
•	Data Visualization (optional extension): Power BI, Matplotlib, Seaborn


**Impact**
•	Fully automated ETL reduced manual processing time by 80%
•	Enabled near real-time analytics for sales and customer metrics
•	Delivered high-quality, reusable datasets to downstream analytics teams

