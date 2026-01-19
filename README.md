# Data-Engineering-Project
Overview
This project is an end-to-end data engineering pipeline built on Databricks Free Edition. It demonstrates how to consolidate data from two companies in the FMCG (Fast-Moving Consumer Goods) domain after an acquisition. The pipeline follows a Medallion Architecture (Bronze, Silver, Gold) to organize, clean, and enrich data, making it analytics-ready for business intelligence.
The project is suitable for beginners and advanced users and provides hands-on experience with real-world industry use cases, including incremental data processing, data lakehouse management, and structured analytics.

Project Objective
Scenario: A large retail company acquires a smaller company with unstructured data.
Goal: Build a robust ETL pipeline to consolidate data from both companies into a single lakehouse architecture.
Approach:
Organize both companies’ data into Bronze (raw), Silver (cleaned), and Gold (curated) layers.
Merge the smaller company’s data with the larger company’s structured data.
Implement a daily scheduled incremental pipeline to ingest new data from Amazon S3.

Tech Stack
Python – ETL scripting and Spark jobs
SQL – Data transformations and aggregations
Apache Spark – Scalable distributed processing
Amazon S3 – Raw and incremental data storage
Databricks Lakehouse – Unified storage and processing environment
Medallion Architecture – Bronze (raw), Silver (cleaned), Gold (curated)
BI Dashboard – Analytics and reporting on Gold layer
