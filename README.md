# 📊 Superstore Data Warehouse Project using SQL

![SQL Server](https://img.shields.io/badge/SQL%20Server-Microsoft-blue?logo=microsoftsqlserver)
![Data Warehouse](https://img.shields.io/badge/Data%20Warehouse-Star%20Schema-orange)
![ETL](https://img.shields.io/badge/ETL-Process-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Intermediate%20to%20Advanced-purple)
![Domain](https://img.shields.io/badge/Domain-Retail%20Analytics-yellow)
![Tools](https://img.shields.io/badge/Tools-SSMS%20%7C%20SQL-lightgrey)
![Made With](https://img.shields.io/badge/Made%20With-SQL-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🧠 Project Overview

This project focuses on building a **Data Warehouse using SQL** from a raw retail dataset and performing business analysis to generate meaningful insights.

The project simulates a real-world scenario where raw data is transformed into a structured format using a **Star Schema** and analyzed for decision-making.

---

## 🎯 Objectives

* Build a **Data Warehouse Architecture**
* Perform **Data Cleaning & Transformation**
* Design **Fact and Dimension Tables**
* Apply **SQL Joins, Aggregations, and Window Functions**
* Generate **Business Insights**

---

## 🏗️ Data Architecture

```
RAW DATA (SUPERSTORE_3)
        ↓
Data Cleaning (TRY_CAST, NULL Handling)
        ↓
Dimension Tables (DIM Tables)
        ↓
Fact Table (FACT_SALES)
        ↓
Business Analysis
```

---

## ⭐ Data Model (Star Schema)

### 🔹 Fact Table:

* **FACT_SALES**

  * ORDER_ID
  * CUSTOMER_ID
  * PRODUCT_ID
  * POSTAL_CODE
  * ORDER_DATE
  * SALES
  * PROFIT
  * QUANTITY
  * DISCOUNT

### 🔹 Dimension Tables:

* **DIM_CUSTOMER**
* **DIM_PRODUCT**
* **DIM_REGION**
* **DIM_DATE**

---

## ⚙️ Key Features

✔ Data Cleaning (NULL & Empty Handling)
✔ Data Type Conversion using `TRY_CAST()`
✔ Duplicate Removal using `ROW_NUMBER()`
✔ Primary Keys & Foreign Keys Implementation
✔ Indexing for Performance Optimization
✔ Star Schema Data Modeling

---

## 💻 SQL Techniques Used

* Joins (INNER JOIN)
* Aggregations (`SUM`, `COUNT`)
* Window Functions (`RANK()`)
* Data Type Conversion (`TRY_CAST`)
* CTE (Common Table Expressions)
* Indexing & Constraints

---

## 📊 Business Analysis

### 🔥 Total Revenue & Profit

* Calculated overall business performance

### 👥 Top Customers

* Identified highest revenue-generating customers

### 📦 Category Performance

* Analyzed revenue across product categories

### 📅 Monthly Trends

* Evaluated sales trends over time

### 🌍 Region-wise Analysis

* Compared performance across regions

### 📈 Profit Margin Analysis

* Measured profitability by category

---

## 📈 Key Insights

* Technology category generates the highest revenue
* A small group of customers contributes a large portion of sales
* Monthly sales show consistent growth patterns
* Regional performance varies significantly

---

## 🧠 Skills Demonstrated

* SQL (Intermediate to Advanced)
* Data Cleaning & Transformation
* Data Modeling (Star Schema)
* Data Warehousing Concepts
* Analytical Thinking
* Business Insight Generation

---

## 🏆 Project Outcome

* Successfully built a **Data Warehouse using SQL**
* Converted raw data into structured analytical model
* Generated insights for business decision-making
* Created a project suitable for **Data Analyst roles**

---

## 🚀 How to Run

1. Import dataset into SQL Server
2. Execute SQL scripts step-by-step:

   * Data Cleaning
   * Dimension Tables Creation
   * Fact Table Creation
   * Constraints & Indexes
   * Analysis Queries

---

## 📌 Future Improvements

* Build Power BI Dashboard for visualization
* Automate ETL process using Python
* Add more advanced SQL queries

---

## 👨‍💻 Author

**JIJI BABU**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and connect with me!
