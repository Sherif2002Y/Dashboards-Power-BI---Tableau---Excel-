# 📊 Power BI Sales & Customer Analytics (RFM) Dashboard
**Project completed at Epsilon AI Academy, Egypt** 🎓

## 📝 Project Overview
This project is an end-to-end **Business Intelligence Solution** that transforms "dirty" raw sales data into actionable business insights. The primary goal was to analyze sales performance and implement advanced customer segmentation to drive targeted marketing and retention strategies.

## 🖥️ Executive Dashboard Highlights
The final report features a modern, interactive UI designed for deep-dive analysis across multiple business dimensions.

![Sales Activity Summary](https://github.com/Sherif2002Y/Dashboards-Power-BI---Tableau---Excel-/blob/main/Sales%20Dashboard%20%26%20RFM%20Model/Screenshots/Summary%20Analysis.png)
<p align="center"><i>Figure 1: Executive Summary showing Sales & Profit Trends, Category distribution, and Regional performance.</i></p>

## 🚀 Key Features
* **Full ETL Process:** Cleaned and transformed unstructured raw data using **Power Query**.
* **RFM Customer Segmentation:** Categorized customers into 11 distinct groups (Champions, Loyal, At Risk, Lost, etc.) to identify high-value targets and churn risks.
* **Interactive Dashboards:**
    * Sales performance by Year, Category, and Country.
    * Top & Bottom performing products.
    * Customer retention and growth trends.
* **Data-Driven Recommendations:** Developed strategic suggestions for each customer segment (Upselling, Reactivation, etc.).

---

## 🏗️ Data Architecture: Star Schema
To ensure high performance and accurate DAX calculations, I designed a robust **Star Schema**. This architecture separates transactional data (Fact) from descriptive data (Dimensions).

![Star Schema Model](https://github.com/Sherif2002Y/Dashboards-Power-BI---Tableau---Excel-/blob/main/Sales%20Dashboard%20%26%20RFM%20Model/Screenshots/star%20schema.png)
<p align="center"><i>Figure 2: Data Model showing 1:Many relationships and optimized filter directions.</i></p>

### Model Components:
* **Fact Tables:**
    * `Fact - Sales`: Central transaction table for revenue and costs.
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

## 📂 How to Explore
1.  **View Report:** [Link to view the dashboard](https://www.linkedin.com/feed/update/urn:li:activity:7394471229598093312/?originTrackingId=UztAgwGGTzO7ywh1XrXvWA%3D%3D)
2.  **Screenshots:** Check the `/Screenshots` folder in this repo.
3.  **Data Model:** Refer to the Star Schema image above.

---

## 📫 Connect with me
* **LinkedIn:** [Sherif Yasser](https://www.linkedin.com/in/sherif-yasser-44950127b/)

* **Email:** sherifyasser19@gmail.com
