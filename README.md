# AtliQ Sales Insights 📊 (End-to-End SQL + Power BI)

## 📌 Project Overview
Successfully executed an end-to-end data analysis project for **AtliQ Hardware**, a computer hardware manufacturer. This project involved transforming **150,000+ rows of raw, messy transactional data** into an automated, interactive Power BI dashboard to replace a fragmented and unreliable manual reporting system.



---

## 🏢 The Business Case
AtliQ Hardware faced a critical challenge: **declining sales** despite a dynamically growing market. The Sales Director, Bhavin Patel, struggled with:
* **Data Fragmentation:** Insights were buried across 60+ Excel files, making consolidation nearly impossible.
* **Lack of Transparency:** Regional managers provided "sugar-coated" verbal updates that didn't match the declining revenue.
* **Vague Requirements:** Business needs were initially unclear. I bridged this gap using the **AIMS Grid** framework to define a precise data strategy.

### 🎯 Project Planning (AIMS Grid)
| Component | Details |
| :--- | :--- |
| **Purpose** | Unlock hidden sales insights and enable data-driven decision-making. |
| **Stakeholders** | Sales Director, Marketing Team, IT (Falcons), and Data Analytics (Data Masters). |
| **End Result** | An automated Power BI dashboard providing a **"Single Source of Truth."** |
| **Success Criteria** | 10% reduction in manual effort and a 5% increase in sales through targeted insights. |

---

## 🛠️ Technical Workflow & Integration

### 1. Data Discovery & SQL Analysis
I performed deep data discovery using **MySQL** to validate the raw data before visualization.
* **Live Connection:** Established a direct connection between the MySQL database and Power BI.
* **Validation:** Identified "dirty" data, including negative values, mismatched currency, and irrelevant regional records.
* **Aggregation:** Analyzed trends by year, month, and region to cross-verify Power BI results.

### 2. ETL & Data Cleaning (Power Query)
Real-world data is messy. I performed extensive **Data Wrangling** in Power Query:
* **Currency Normalization:** Standardized mixed currency (USD and INR) into a single metric using Power Query and DAX.
* **Data Sanitization:** Removed transactions with zero or negative sales amounts to ensure accuracy.
* **Region Filtering:** Cleaned out non-relevant regional records (e.g., New York, Paris) to focus strictly on Indian markets.
* **Star Schema Modeling:** Designed a robust Star Schema for efficient analytical querying.



### 3. Dashboard Engineering
The final dashboard provides executive-level KPIs:
* **Revenue & Sales Quantity** trends over time.
* **Revenue Breakdown** by Region, Customer, and Product.
* **Top 5 Customers & Products** to prioritize high-value segments.
* **Time Intelligence:** Year-over-Year (YoY) and Monthly growth slicers.

---

## 📈 Business Impact
* **Single Source of Truth:** Eliminated manual Excel merging, saving **20+ man-hours per month**.
* **Actionable Insights:** Exposed a significant revenue dip in 2020 that was previously obscured by verbal reports.
* **Decision Support:** Identified underperforming regions (e.g., Bengaluru) where the sales team can now launch targeted promotion offers.

---

## 🧰 Tools & Skills Demonstrated
* **SQL (MySQL):** Joins, Aggregations, Data Discovery, Verification.
* **Power BI Desktop:** Data Modeling, Star Schema, Visual Storytelling.
* **Power Query (M):** ETL, Data Cleaning, Currency Normalization.
* **DAX:** Calculated Measures, Time-Intelligence functions.
* **Project Management:** AIMS Grid framework, Stakeholder Management.

---

## 📂 Repository Contents
* `db_dump.sql`: The raw SQL data dump.
* `SQL_Analysis_Queries.sql`: SQL scripts used for initial discovery.
* `atiq-az.pbix`: The final Power BI project file.
