# 🛒 E-commerce Sales & Customer Analytics using SQL, Python, and Power BI

## 📌 Project Overview

This project focuses on analyzing e-commerce sales data to identify trends in revenue, product performance, customer behavior, and profitability. 
The analysis was performed using Python for data cleaning and EDA, SQL for business queries, and Power BI for interactive dashboards to support data-driven decision-making.

---

## 🎯 Objectives

* Clean and preprocess raw superstore data
* Store structured data in a relational database (MySQL)
* Perform SQL queries to generate KPIs and insights
* Build interactive dashboards using Power BI
* Identify profit drivers, loss areas, and growth opportunities

---

## 📂 Dataset

* **Type:** Retail Superstore Sales Data
* **Data Includes:**

  * Order details
  * Customer information
  * Product categories & sub-categories
  * Sales, profit, quantity, discount
  * Shipping mode
  * Region & segment

---

## ⚙️ Tools & Technologies Used

| Tool / Technology | Purpose                                |
| ----------------- | -------------------------------------- |
| Python            | Data cleaning & transformation         |
| Pandas            | Data preprocessing                     |
| MySQL             | Data storage & SQL analysis            |
| SQL               | KPI extraction & business queries      |
| Power BI          | Interactive dashboards & visualization |

---

## 🔍 Project Workflow

### 1️⃣ Data Cleaning & Transformation

* Loaded raw superstore data using **Pandas**
* Removed inconsistencies and prepared data for analysis
* Structured data into tabular format

### 2️⃣ Database Integration (MySQL)

* Imported cleaned dataset into **MySQL**
* Created a `superstore` table
* Performed multiple SQL queries to extract insights

### 3️⃣ SQL Analysis & KPIs

Key KPIs generated using SQL:

* Total Sales
* Total Profit
* Total Quantity Sold
* Distinct Customers Count

**KPI Summary:**

* 💰 Sales: ~2.27M
* 📈 Profit: ~282.86K
* 📦 Quantity: ~37K
* 👥 Customers: 793

---

## 📊 Key Analyses Performed

### 📅 Sales & Profit Trends

* Quarterly and yearly trend analysis (2014–2017)
* Identified seasonal peaks (Q4 performance)

### 🧾 Category Analysis

* Technology is the most profitable category
* Furniture shows lowest profit contribution

### 🌍 Regional Performance

* West region contributes highest profit
* South region underperforms

### 🧑‍🤝‍🧑 Customer & Segment Insights

* Consumer segment generates maximum profit
* Home Office segment lags behind

### 🚚 Shipping Analysis

* First Class shipping delivers fastest (avg ~2.3 days)

### 💸 Discount & Profitability

* 808 orders with >50% discount but negative profit
* Indicates inefficient discount strategies

### 📦 Product Performance

* Copiers, Phones, Accessories are top performers
* Tables & Bookcases show high sales but low profit margins

---

## 📈 Power BI Dashboard Features

* KPI Cards (Sales, Profit, Quantity)
* Profit by Year & Quarter (Line Chart)
* Profit by Category & Region (Pie Charts)
* Profit by Segment (Donut Chart)
* Profit by Sub-Category (Bar Chart)
* Interactive filters (Region, Category, Year)

---

## 🧠 Business Insights & Recommendations

### 🔹 Profit Growth

* Strong upward profit trend from 2014–2017
* Seasonal peaks in Q4

**Recommendation:** Increase inventory & marketing before peak seasons

### 🔹 Category Strategy

* Technology drives over 50% of profit
* Furniture underperforms

**Recommendation:** Promote Technology, re-evaluate Furniture pricing

### 🔹 Regional Optimization

* West & East regions generate ~70% of profit
* South region needs improvement

**Recommendation:** Region-specific strategies & logistics review

### 🔹 Discount Control

* High discounts lead to losses

**Recommendation:** Reassess discount policies on low-margin products

---

## 🏗️ System Architecture

* **Data Processing:** Python (Pandas)
* **Database Layer:** MySQL
* **Analysis Layer:** SQL Queries
* **Visualization Layer:** Power BI Dashboard

---

## 🚀 Future Enhancements

* Automate data pipeline using ETL tools
* Add predictive analytics (sales forecasting)
* Integrate Python with Power BI for live updates
* Deploy dashboards on Power BI Service

---

## 👨‍🎓 Author

* **Kuldeep Patidar**
  Data Analyst / Data Science Student

---

## 📜 Conclusion

This project showcases the power of combining **Python, SQL, and Power BI** for business analytics. By transforming raw retail data into insightful dashboards and recommendations, the project demonstrates practical data analysis skills applicable to real-world business problems.

⭐ *If you like this project, don’t forget to star the repository!*

