# AtliQ Hardware Sales Insights 📊 (End-to-End SQL + Power BI)

## 📌 Project Overview
Successfully executed an end-to-end data analysis project for **AtliQ Hardware**, a computer hardware manufacturer. This project involved transforming **150,000+ rows of raw, messy transactional data** into an automated, interactive Power BI dashboard to replace a fragmented manual reporting system.

---

## 🏢 The Business Case
AtliQ Hardware faced a critical challenge: **declining sales** in a dynamically growing market. The Sales Director was struggling with:
* **Data Fragmentation:** Insights were buried in 60+ Excel files.
* **Lack of Transparency:** Regional managers provided "sugar-coated" verbal updates.
* **Vague Requirements:** Business needs were initially unclear. I utilized the **AIMS Grid** framework to define a precise project strategy.

### 🎯 Project Planning (AIMS Grid)
* **Purpose:** To unlock hidden sales insights and enable data-driven decision-making.
* **Stakeholders:** Sales Director, Marketing Team, IT, and Data Analytics.
* **End Result:** An automated Power BI dashboard providing a "Single Source of Truth."
* **Success Criteria:** 10% reduction in manual effort and a 5% increase in sales through targeted insights.

---
## 🧰 Tools & Skills Demonstrated
* **SQL (MySQL):** Joins, Aggregations, Data Discovery.
* **Power BI Desktop:** Data Modeling, Star Schema, Dashboard Design.
* **Power Query (M):** ETL, Data Cleaning, Currency Conversion.
* **DAX:** Calculated Measures, Time-Intelligence functions.
* **Project Management:** AIMS Grid, Stakeholder Management.

---

## 🛠️ Technical Workflow & Integration

### 1. Data Discovery & SQL Analysis
I performed deep data discovery using **MySQL** to validate the raw data before visualization.
* **Live Connection:** Established a direct connection between the **MySQL database** and **Power BI**.
*  Explore and validate raw data
*  Aggregate revenue and sales quantity
*  Analyze trends by year, month, region, customer, and product
*  Cross-verify Power BI results for accuracy

### 2. ETL & Data Cleaning (Power Query)
Real-world data is messy. I performed extensive **Data Wrangling** in Power Query:
* **Currency Normalization:** Used DAX and Power Query to convert all USD transactions to INR.
* **Data Sanitization:** Removed transactions with zero or negative sales amounts.
* **Region Filtering:** Cleaned out non-relevant regional records to maintain focus on Indian markets.
* **Star Schema Modeling:** Star schema for efficient analytics  

### 3. Dashboard Engineering
The final dashboard provides executive-level KPIs including:
* **Revenue & Sales Quantity** trends.
* **Revenue Breakdown** by Region, Customer, and Product.
* **Top 5 Customers & Products** identification.
* **Year-over-Year (YoY)** and Monthly growth slicers.

---

## 📈 Business Impact
* **Single Source of Truth:** Eliminated the need for manual Excel merging, saving 20+ man-hours per month.
* **Actionable Insights:** Exposed a significant revenue dip in 2020 that was previously obscured by verbal reports.
* **Decision Support:** Identified underperforming regions (e.g., Bengaluru) where the sales team could launch targeted promotion offers.

---


## 📂 Repository Contents
* `db_dump.sql`: The raw SQL data dump.
* `SQL_Analysis_Queries.sql`: SQL scripts used for initial discovery.
* `atiq-az.pbix`: The Power BI project file.

