# Airbnb Data Engineering Project

## 📌 Project Overview
This project demonstrates an end-to-end **modern data engineering pipeline** built using **AWS, Snowflake, and dbt** to process and analyze Airbnb data. The goal is to ingest raw data, transform it into analytics-ready tables, and enable meaningful insights using best practices from the modern data stack.

---

## 🏗️ Architecture
The project follows a layered data architecture:

1. **Data Ingestion**
   - Raw Airbnb datasets are ingested and stored in AWS S3.

2. **Data Storage & Warehousing**
   - Snowflake is used as the cloud data warehouse.
   - Raw data is loaded from S3 into Snowflake staging tables.

3. **Data Transformation**
   - dbt is used to transform raw data into clean, structured, and analytics-ready models.
   - Models follow the **staging → intermediate → mart** approach.

4. **Analytics & Reporting**
   - Final fact and dimension tables can be used for BI tools or analytical queries.

---

## 🛠️ Tech Stack
- **Cloud Platform:** AWS (S3, IAM)
- **Data Warehouse:** Snowflake
- **Transformation Tool:** dbt
- **Languages:** SQL
- **Version Control:** Git & GitHub


