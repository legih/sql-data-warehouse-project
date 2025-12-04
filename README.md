📦 Data Warehouse Project (SQL-Only)

This repository contains my first end-to-end Data Warehouse project, designed and built entirely using SQL.
The goal of this project is to demonstrate foundational concepts of data engineering, including data modeling, ETL pipeline design, and multi-layered architecture using SQL-based transformations.

🚀 Project Overview

This project implements a three-layer Data Warehouse architecture:

1. Bronze Layer

Stores raw CRM and ERP data

No transformations

Full load using truncate-and-insert

2. Silver Layer

Cleaned, standardized, and enriched data

Transformations include:

Data cleansing

Normalization

Derived columns

Data enrichment

Ready for integration into analytics models

3. Gold Layer

Final business-ready views

Implements:

Star schema

Aggregated tables

Business logic and KPIs

Used directly by reporting and BI tools

🛠️ Technologies Used

SQL Server (DDL + DML)

T-SQL Stored Procedures

View-based fact & dimension modeling

📂 Project Components

/bronze – Raw table DDL + load procedures

/silver – Clean & conformed table DDL + ETL logic

/gold – Final fact/dimension views for analytics

/diagrams – Architecture diagrams

README.md – Project documentation

🎯 Learning Outcomes

Through this project, I learned how to:

Build a Data Warehouse from scratch using SQL

Design multi-layer ETL pipelines

Create star schemas for analytics

Work with real-life CRM & ERP datasets

Apply best practices in data cleaning and transformation

📌 Status

✔️ Completed – initial version of full SQL-based Data Warehouse
🔧 Future enhancements planned – incremental loads, SCDs, more facts/dimensions
