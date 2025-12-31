# 📊 Excel Sales Performance & Customer Analytics (RFM) Dashboard

**Advanced Business Intelligence Solution**

## 📝 Project Overview

This project involved building a sophisticated BI solution within Microsoft Excel to analyze sales performance and customer loyalty. By leveraging Excel’s modern "Power" suite, I transformed disorganized datasets into a professional-grade analytical tool featuring automated ETL and behavioral customer segmentation.

## 🚀 Key Technical Features

* **Automated ETL with Power Query:** Connected to raw data sources to clean, pivot, and merge datasets. I implemented custom M-Language transformations to handle null values and ensure data consistency.
* **Power Pivot Data Modeling:** Built a robust **Star Schema** directly within the Excel Data Model. Established 1:Many relationships between Fact and Dimension tables to ensure calculation speed and data integrity.
* **Advanced DAX in Excel:** Authored complex measures using Data Analysis Expressions (DAX) within Power Pivot, including:
* **Time-Intelligence:** YoY Growth and Month-over-Month comparisons.
* **Customer Metrics:** Retention Rate, Churn Rate, and Customer Lifetime Value (CLV).


* **RFM Behavioral Scoring:** Developed a logic-based scoring system to categorize customers into 11 actionable segments (e.g., Champions, At Risk, Lost) to drive targeted marketing.
* **Dynamic UI/UX:** Designed a professional dashboard using Slicers, Timeline filters, and Dynamic Charts that allow users to drill down into specific regions, categories, or time periods.

---

## 🏗️ The Data Architecture: Excel Star Schema

To move beyond the limitations of standard VLOOKUPs, I utilized a **Star Schema** architecture. This separates transactional data from descriptive attributes, resulting in a significantly faster and more scalable workbook.

* **Fact Tables:** `Sales_Data`, `RFM_Scores`.
* **Dimension Tables:** `Dim - Customer`, `Dim - Product`, `Dim - Geography`, `Dim - Category`, and `Dim - Calendar`.
---

## 🛠️ Technical Stack

* **Microsoft Excel:** Core platform for the final dashboard.
* **Power Query (M):** For automated data cleaning and transformation.
* **Power Pivot (DAX):** For data modeling and advanced analytical calculations.
* **Pivot Tables & VBA:** (Optional, mention if used) Used for advanced interactivity and report automation.

---

## 📈 Actionable Insights & Recommendations

The dashboard doesn't just show data; it suggests strategy:

* **Champions:** Strategy for loyalty programs and referrals.
* **At Risk Customers:** Automated identification for "Win-back" email campaigns.
* **Product Performance:** Identified "Sleeping Giants" (high-margin, low-volume products).

---

## 📂 How to Explore
1.  **View Report:** [Link to view the dashboard]()
2.  **Screenshots:** Check the `/Screenshots` folder in this repo.

---


## 📫 Connect with me
* **LinkedIn:** [Sherif Yasser](https://www.linkedin.com/in/sherif-yasser-44950127b/)

* **Email:** sherifyasser19@gmail.com