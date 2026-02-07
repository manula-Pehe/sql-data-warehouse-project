# SQL Data Warehouse Project

## 📌 Overview
This project demonstrates how to build a data warehouse from scratch using **SQL only**.  
It follows a layered architecture (Bronze, Silver, Gold) to transform raw data into analytics-ready datasets.

The goal of this project is to showcase core data warehousing concepts such as:
- Data ingestion using SQL
- Data cleansing and transformation
- Star schema modeling
- Analytical querying

---

## 🏗 Architecture
The project is organized into three layers:

### 🥉 Bronze Layer
- Stores raw data ingested from source files
- Minimal or no transformations applied

### 🥈 Silver Layer
- Cleansed and standardized data
- Handles duplicates, null values, and data consistency

### 🥇 Gold Layer
- Analytics-ready data
- Fact and dimension tables modeled using a star schema

---

## 🧱 Data Modeling
The data warehouse uses a **Star Schema** consisting of:
- Fact tables for business metrics
- Dimension tables for descriptive attributes (date, customer, product, etc.)

---

## 🛠 Technologies Used
- SQL
- SQL Server
- CSV datasets

---

## 📊 Analytics
Sample analytical queries are included to demonstrate:
- Trend analysis
- Aggregations
- Business insights

---

## 🚀 Learning Outcomes
- Understanding data warehouse architecture
- Writing ETL logic using SQL
- Designing star schemas
- Performing analytical queries
