# BI Insight & Performance Intelligence 📊

An analytical Power BI project designed to extract actionable insights from sales and returns data. This project demonstrates end-to-end data preparation, relational data modeling, and the implementation of advanced DAX calculations to track business performance.

## 📌 Project Overview
The goal of this project is to analyze business data to understand total sales, profitability, and product return trends. By leveraging time-intelligence functions, the dashboard compares current metrics against previous year performances to provide a clear view of Year-over-Year (YoY) growth.

## ⚙️ Key Features & Workflow

* **Data Preparation (Power Query):** 
  * Cleaned and transformed raw data from multiple sources.
  * Corrected data types and promoted headers for accurate analysis.
* **Data Modeling:** 
  * Established a **One-to-Many / One-to-One** relationship between the `Sales` and `Returns` tables using a primary key (`Order ID`).
  * Created a dedicated dynamically generated `Calendar` table (`CALENDARAUTO()`) and marked it as the official Date Table.
* **Advanced DAX Measures:**
  * **Core Metrics:** `Total Sales`, `Total Profit`, `Unique Orders`, `Unique Returns`, and `Return Percentage`.
  * **Time-Intelligence:** Calculated `Previous Year Sales` and `Previous Year Profit` using the `SAMEPERIODLASTYEAR()` function.
  * **Performance Tracking:** Developed YoY comparative measures like `Sales Percentage Change` and `Profit Percentage Change` using the `DIVIDE()` function.

## 📂 Dataset Included
* **Sales Table:** Contains transactional data including Order Date, Customer info, Product details, Sales amount, and Profit.
* **Returns Table:** Contains records of returned items and the specific reasons for the returns.

## 🛠️ Tools & Technologies Used
* **Microsoft Power BI Desktop** (Data Visualization & Modeling)
* **Power Query Editor** (ETL - Extract, Transform, Load)
* **DAX** (Data Analysis Expressions)

## 👨‍💻 Author
**Bayzid Mostak**  
Data Analyst  
*Passionate about data modeling, business intelligence, and uncovering actionable insights from complex datasets.*
