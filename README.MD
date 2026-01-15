# End-to-End Lakehouse Pipeline (Databricks)

## 📌 Project Overview
This project demonstrates a modern **Medallion Architecture** (Bronze -> Silver -> Gold) pipeline using **Azure Databricks** and **PySpark**. 
It is designed to handle high-volume data ingestion, mimicking the scale of 80L+ records I managed during my time at Accenture.

## 🛠 Tech Stack
* **Compute:** Azure Databricks (Spark 3.3)
* **Storage:** Delta Lake (Parquet)
* **Language:** PySpark & SparkSQL
* **Orchestration:** Databricks Workflows (simulated)

## 🚀 Key Features
1.  **Bronze Layer:** Raw data ingestion with schema enforcement (Auto Loader).
2.  **Silver Layer:** Data quality checks, deduplication, and NULL handling.
3.  **Gold Layer:** Business-level aggregations ready for PowerBI/Tableau.

## 🔄 Migration Insight (IICS to Databricks)
As an IICS developer, I built this pipeline to replicate a standard "Mapping Task" using code. 
Check the `migration_scripts/` folder to see how standard ETL logic is optimized for Spark clusters.
