# SQL-Data-Warehouse-Project
Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.
Welcome to the **Data Warehouse and Analytics Project** repository!🚀 
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project highlights industry best practices in data engineering and analytics.

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of r data model to support both business stakeholders and analytics teams.

##

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**
These insights empower stakeholders with key bussiness metrics, enabling strategic decision-making.

# Data Architecture

The data architecture for this project follows the Medallion Architecture with three layers: Bronze, Silver, and Gold.

You can see the high-level architecture here:

[![High-Level Architecture](https://github.com/Angelgralsh/sql-data-warehouse-project/blob/main/docs/data_architecture.png)

* **1. Bronze Layer**: Stores raw data as-is from source systems. Data is ingested from CSV files into a SQL Server Database.

* **2. Silver Layer**: This layer involves data cleansing, standardization, and normalization to prepare the data for analysis.

* **3. Gold Layer**: Contains business-ready data, modeled into a star schema for reporting and analytics.

### License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

### About Me
Hi there! I'm **Angelica Grajales**  I'm an IT professional and passionate about learning new concepts and tools

---

---
