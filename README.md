# Data Engineering Portfolio — Amee Joshi

Cloud data pipelines · Lakehouse architecture · Azure Databricks · Production-grade ETL

---

## About

Data Engineer specialising in Azure cloud platforms, backed by **8+ years building production systems** and **1+ year focused on data engineering**. This portfolio covers end-to-end builds across the full DE stack — raw ingestion, pipeline design, data modelling, and analytics delivery — primarily on Azure.

Currently working toward the **DP-700 Microsoft Fabric Data Engineer Associate** certification · EU work authorisation
🔗 [LinkedIn](https://www.linkedin.com/in/amee-joshi-09b77754/)

---

## Featured Projects

### [Azure Databricks End-to-End Retail Lakehouse](https://github.com/AmeeJoshi-MCA/azure-databricks-end-to-end-retail-lakehouse)
`Databricks` `Auto Loader` `Delta Lake` `Unity Catalog` `PySpark` `Medallion Architecture` `SCD Type 1 & 2`

Retail data presents a specific challenge: products change price and category over time, customers update their details, and orders arrive continuously. This project addresses that with a full Bronze–Silver–Gold lakehouse — Auto Loader for incremental file ingestion, SCD Type 1 for customers (latest state), SCD Type 2 for products (full history with effective dates), and an append-only FactOrders table. Gold dimensions are joined at query time, not at load time.

---

### [Azure End-to-End Data Engineering — AdventureWorks](https://github.com/AmeeJoshi-MCA/azure-end-to-end-data-engineering-adventure-works)
`ADF` `ADLS Gen2` `Databricks` `Synapse Analytics` `Medallion Architecture`

Enterprise pipelines break when a new source gets added and someone has to rewrite the ingestion logic. This project solves that with a fully metadata-driven ADF layer — add a source to the config, the pipeline adapts. Medallion Architecture processing in Databricks, Delta format throughout, and a Synapse Analytics serving layer with external tables and SQL views ready for Power BI.

---

### [SQL Server Data Warehouse & Analytics](https://github.com/AmeeJoshi-MCA/SQL-Server-DataWarehouse-and-Analytics)
`SQL Server` `T-SQL` `Star Schema` `ETL` `Medallion Architecture`

How do you build a warehouse that stays consistent as source data changes? This project implements a Medallion-layered Star Schema in SQL Server — T-SQL ETL pipelines with reconciliation checks, dimensional modelling, and a clean single source of truth for analytics and reporting.

---

### [Spotify End-to-End Azure Data Engineering Pipeline](https://github.com/AmeeJoshi-MCA/Spotify-EndToEnd-Azure-Data-Engineering-Pipeline)
`Databricks Asset Bundles` `Delta Live Tables` `Spark Structured Streaming` `CDC` `ADF` `Unity Catalog`

Most portfolio projects are built and run manually — this one is deployed like production. The pipeline uses Databricks Asset Bundles (DABs) for Infrastructure-as-Code deployment, Delta Live Tables for Bronze–Silver processing, Spark Structured Streaming in the Silver layer with file-based Delta paths registered into Unity Catalog after stabilisation, and ADF watermark-based incremental loading for CDC with SCD Type 1. Managed Identity-based access throughout — no hardcoded credentials.

---

## More Projects

| Project | Stack | What it demonstrates |
|---|---|---|
| [Bank Loan Data Analysis](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis) | SQL, Python, Power BI, Tableau, Excel | End-to-end pipeline from raw loan data to multi-tool BI layer; KPI tracking and risk segmentation |
| [Azure Dynamic Ingestion Framework](https://github.com/AmeeJoshi-MCA/Azure-Data-Engineering-Framework-Dynamic-Ingestion) | ADF, Azure | Reusable metadata-driven ingestion — no hardcoded pipeline logic per source |
| [Enterprise ADF Data Engineering](https://github.com/AmeeJoshi-MCA/Azure-data-factory-enterprise-data-engineering) | ADF, Logic Apps, GitHub CI/CD | Modular ingestion from on-prem, REST APIs, and Azure SQL; delta loads, MERGE operations, Logic App alerting |
| [AdventureWorks Excel Sales Dashboard](https://github.com/AmeeJoshi-MCA/AdventureWorks-Excel-Sales-Analytics-Dashboard) | Excel, Power Query, Power Pivot, DAX | Star schema and DAX measures inside Excel for YoY growth and customer profitability |
| [Spotify User Behaviour Analytics](https://github.com/AmeeJoshi-MCA/Spotify-User-Behavior-Analytics-PowerBI) | Power BI, DAX | Complex DAX, heat maps, quadrant analysis across 11 years of behavioural data |
| [Social Media Ad Performance](https://github.com/AmeeJoshi-MCA/Social-Media-Ad-Performance) | SQL, Power BI, DAX | Funnel metrics (CTR, conversion, ROI) across demographics for Meta ad campaign analysis |
| [Blinkit Analysis](https://github.com/AmeeJoshi-MCA/Blinkit-Analysis) | SQL, Python, Power BI | Full SQL–Python–BI pipeline for inventory optimisation and revenue analysis |

---

## Stack

**Cloud & Platforms**
Azure Databricks · Azure Data Factory · ADLS Gen2 · Synapse Analytics · Unity Catalog

**Languages**
Python · PySpark · SQL · Spark SQL

**Data Engineering**
Medallion Architecture · Delta Lake · Auto Loader · Delta Live Tables · Incremental Loading · SCD Type 1 & 2 · CDC · Star Schema · Data Quality & Validation

**Storage**
Delta · Parquet · Partitioned Data Storage

**BI & Analytics**
Power BI · DAX · Tableau · Excel (Power Pivot)

**DevOps**
Git · CI/CD · Databricks Asset Bundles
