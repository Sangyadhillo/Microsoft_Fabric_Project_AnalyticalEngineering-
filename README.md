# Microsoft_Fabric_Project_AnalyticalEngineering

# 🚀 Project 2: Analytics Engineering with Microsoft Fabric & Snowflake

This project demonstrates end-to-end data ingestion and processing using Microsoft Fabric, Snowflake, and SQL Analytics.

## 📦 Key Components

- **Development Workspace Setup**  
- **Lakehouse Architecture**
  - Created a *Landing Lakehouse* for initial data collection
  - Final *Lakehouse* for refined, query-ready data

## 🔄 Data Flow Pipeline

1. Ingested `fact_orders` data from Snowflake into Fabric Lakehouse
2. Created pipelines to automate movement:
   - From **Snowflake → Landing Lakehouse**
   - From **Landing Lakehouse → Final Warehouse (table)**
   - From **Final Warehouse → Final Lakehouse**
3. Added all CSV files to the Dataflow
4. Configured destinations and verified data integrity

## 📊 Analytics Access

- Enabled **SQL Analytics Endpoint** for read-only access
- DML operations restricted to ensure data security
- This endpoint provides query access to stakeholders without direct Lakehouse access

## 📈 Reporting

Final step: Built a report on top of the SQL Analytics Endpoint using Power BI for end-user consumption.

---

🛠️ Tech Stack:
- Microsoft Fabric
- Snowflake
- Power BI
- Data Pipelines
