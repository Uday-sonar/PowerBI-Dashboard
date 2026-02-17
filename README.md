# 📊 SQL Analysis: Superstore Sales Performance

This project demonstrates a comprehensive data analysis of a retail dataset using **SQL**. It focuses on extracting actionable business insights from the `superstore_sales` table by performing aggregations, filtering, and subqueries to evaluate performance across customers, regions, and product categories.

## Table of Contents
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Analysis Steps Performed](#analysis-steps-performed)
- [Project Structure](#project-structure)
- [Key Insights & Results](#key-insights--results)
- [How to Run](#how-to-run)

---

## 📌 Objective
The goal of this project is to leverage SQL to analyze sales performance and profitability within the `superstore_db`.

**Key Metrics Addressed:**
* Identifying high-value customers with sales > $300.
* Calculating total revenue and average profitability.
* Benchmarking regional performance by profit.
* Analyzing sales distribution across product categories.

---

## 🛠 Tech Stack
* **Language:** SQL (MySQL) 
* **Database:** `superstore_db` 
* **Presentation:** Microsoft PowerPoint
* **Data Focus:** Retail/E-commerce Sales 

---

## ⚙️ Analysis Steps Performed

### 1. Database Setup & Exploration
Initialized the environment by creating the database and verifying the raw data structure.
> **Query:** `SELECT * FROM superstore_sales LIMIT 5000;`

### 2. Profitability Analysis
* **Averages:** Calculated the average profit per transaction, which was approximately **35.57**.
* **Top Products:** Used subqueries to isolate the specific product with the maximum profit (**Atlantic Metals Mobile 3-Shelf Bookcases**).

### 3. Customer Insights
* **High-Spenders:** Filtered for individual transactions exceeding **$300**.
* **Top 10 Customers:** Aggregated total sales per customer and ranked them to find top contributors, led by **Claudia Bergmann** ($1,672.31).

### 4. Regional & Category Summaries
* **Regional Profit:** Grouped data by **Region**; the **East** region leads in total profit ($892.05).
* **Category Sales:** Grouped data by **Category**, revealing **Furniture** as the highest sales driver ($6,117.23).

---

## 📊 Key Insights & Results

| Metric | Result |
| :--- | :--- |
| **Total Sales** | $12,926.48 |
| **Average Profit** | $35.57  |
| **Top Region** | East ($892.05 profit)  |
| **Top Category** | Furniture ($6,117.23 sales)  |

---

## 📦 Project Structure
```plaintext
sql-sales-analysis/
│
├── Superstore-Sales_newDashboard.pptx  # Data Visualization & Insights Summary
├── results_export/                     # CSV exports of query results
└── README.md                           # Project Documentation
