# 🚀 Data Warehouse and Analytics Project

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![SSMS](https://img.shields.io/badge/SSMS-Tools-blue?style=for-the-badge)
![Data Engineering](https://img.shields.io/badge/Data%20Engineering-Medallion%20Arch-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📖 Introduction
Welcome to the **Data Warehouse and Analytics Project** repository! 

This project demonstrates a comprehensive data warehousing and analytics solution, illustrating the journey from building a raw data warehouse to generating actionable business insights. Designed as a portfolio piece, it highlights industry best practices in **Data Engineering**, **ETL Pipeline Design**, and **Business Intelligence**.

---

## 🏗️ Data Architecture
The data architecture for this project follows the **Medallion Architecture** pattern, ensuring data quality and lineage through three distinct layers:

### 🥉 Bronze Layer (Raw)
* **Function:** Stores raw data as-is from source systems.
* **Process:** Data is ingested directly from CSV files (ERP & CRM systems) into the SQL Server Database without modification.

### 🥈 Silver Layer (Cleaned)
* **Function:** Validated and enriched data.
* **Process:** Includes data cleansing, standardization, null handling, and normalization processes to prepare data for analytical modeling.

### 🥇 Gold Layer (Business-Ready)
* **Function:** Consumption-ready data for reporting.
* **Process:** Houses data modeled into a **Star Schema** (Fact & Dimension tables) optimized for fast analytical queries and Power BI reporting.

---

## 🔍 Project Overview
This project covers the full data lifecycle:

* **Data Architecture:** Designing a Modern Data Warehouse using Medallion Architecture (Bronze, Silver, Gold).
* **ETL Pipelines:** Extracting, Transforming, and Loading (ETL) data from source systems into the warehouse.
* **Data Modeling:** Developing optimized Fact and Dimension tables for analytical performance.
* **Analytics & Reporting:** Creating SQL-based reports and dashboards to derive actionable insights.

### 🎯 Key Skills Demonstrated
This repository showcases expertise in:
* ✅ SQL Development & Advanced Querying
* ✅ Data Architecture & Dimensional Modeling
* ✅ Data Engineering (ETL Pipelines)
* ✅ Data Analytics & Insight Generation

---

## 🛠️ Tools & Technologies
* **Database:** Microsoft SQL Server (Express Edition)
* **Management:** SQL Server Management Studio (SSMS)
* **Version Control:** Git & GitHub
* **Design:** DrawIO (Schema & Flow diagrams)
* **Source Data:** CSV Datasets (ERP & CRM)

---

## 🚀 Project Requirements & Goals

### 1. Data Engineering (Building the Warehouse)
**Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting.

* **Data Sources:** Import data from ERP and CRM systems (CSV format).
* **Data Quality:** Cleanse and resolve quality issues (nulls, duplicates, formatting) prior to analysis.
* **Integration:** Combine distinct sources into a single, unified data model (Star Schema).
* **Scope:** Focus on current state analysis (Snapshot) without historical data retention (SCD).
* **Documentation:** Maintain clear documentation of the data model for stakeholders.

### 2. Business Intelligence (Analytics & Reporting)
**Objective:** Develop SQL-based analytics to deliver detailed insights.

**Key Metrics Analyzed:**
* 📈 **Customer Behavior:** Purchasing patterns and churn analysis.
* 📦 **Product Performance:** Top-selling categories and underperforming stock.
* 💰 **Sales Trends:** Seasonal trends and revenue growth.

---

