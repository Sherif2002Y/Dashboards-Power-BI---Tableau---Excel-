# 📊 Power BI Sales & Customer Analytics (RFM) Dashboard
**Project completed at Epsilon AI Academy, Egypt** 🎓

## 📝 Project Overview
This project is an end-to-end **Business Intelligence Solution** that transforms "dirty" raw sales data into actionable business insights. The primary goal was to analyze sales performance and implement advanced customer segmentation to drive targeted marketing and retention strategies.

## 🖥️ Executive Dashboard Highlights
The final report features a modern, interactive UI designed for deep-dive analysis across multiple business dimensions.

![Sales Activity Summary](Summary%20Analysis.png)
*Figure 1: Executive Summary showing Sales & Profit Trends, Category distribution, and Regional performance.*

### Key Analytical Pages:
* **Geographic Analysis:** Visualizing global performance with interactive map visuals.
* **RFM Customer Segmentation:** A dedicated deep-dive into customer behavior and loyalty groups.
* **Root Cause Analysis:** Using Decomposition Trees to identify the factors behind bottom-performing products.
* **Sales Forecasting:** "What-If" analysis to predict 2015 sales based on growth and cost parameters.

---

## 🏗️ Data Architecture: Star Schema
To ensure high performance and accurate DAX calculations, I designed a robust **Star Schema**. This architecture separates transactional data (Fact) from descriptive data (Dimensions).

![Star Schema Model](star%20schema.png)
*Figure 2: Data Model showing 1:Many relationships and optimized filter directions.*

### Model Components:
* **Fact Tables:** * `Fact - Sales`: Central transaction table for revenue and costs.
    * `Fact - Customer Profile (RFM Modeling)`: Specialized table for behavioral scoring.
* **Dimension Tables:** `Dim - Customer`, `Dim - Product`, `Dim - Geography`, `Dim - Category`, and `Dim - Calendar`.
* **Key Measures:** Organized into a dedicated folder containing 20+ complex DAX formulas like **Retention Rate (%)**, **Customer Lifetime Value (CLV)**, and **Churn Rate**.

---

## 👥 Customer Intelligence (RFM Analysis)
Using Recency, Frequency, and Monetary scores, I segmented the customer base into **11 groups** to guide business strategy:
* **Champions:** Reward for loyalty.
* **At Risk:** Targeted for reactivation campaigns.
* **New Customers:** Onboarding and upselling focus.

---

## 🛠️ Technical Stack
* **Power BI Desktop:** Core visualization and dashboarding.
* **Power Query:** Data cleaning, transformation, and ETL.
* **DAX (Advanced):** Time-Intelligence, RFM scoring, and forecasting parameters.
* **Data Modeling:** Implementation of Star Schema and Star Schema optimization.

---

## 📫 Connect with me
* **LinkedIn:** [Your Name](Your-Link-Here)
* **Email:** your.email@example.com