## High Level Architecture

![Architecture Diagram](https://github.com/user-attachments/assets/67a18b8c-fae8-4f76-8975-a7a7f99f5a03)

1. **Bronze Layer** - Acts as the ingestion layer for raw data from CSV files from our source systems.
2. **Silver Layer** - Intermediary layer where data transformations and cleansing take place to prepare data for analysis.
3. **Gold Layer** - This is where Business Ready data lives and is modeled out as a star schema for downstream use cases like ML and Reporting.

<br>

<h2 align="center">High Level Architecture</h2>

<h2 align="center">This Project Involves</h2>

- **Data Architecture:** Designing a Modern Data Warehouse using Medallion Architecture (Bronze, Silver, and Gold layers).
- **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.
