# 📊 Sales Analytics Dashboard (Power BI)

## 🚀 Project Overview

This project is a **Sales Analytics Dashboard** built using **Power BI**, designed to provide actionable insights into sales performance, customer behavior, product trends, and campaign effectiveness.

The dashboard enables stakeholders to:

* Monitor overall business performance
* Identify top-performing products and salespersons
* Analyze customer segmentation
* Track sales trends over time
* Evaluate marketing campaign ROI

---

## 📁 Dataset Description

The project follows a **star schema data model**, consisting of one fact table and multiple dimension tables.

### 🔹 Fact Table

**`fact_sales_normalized.csv`**
Contains transactional sales data.

| Column Name      | Description                       |
| ---------------- | --------------------------------- |
| sales_sk         | Surrogate key                     |
| sales_id         | Unique sales identifier           |
| customer_product | Customer-product relationship key |
| store_sk         | Store identifier                  |
| salesperson_sk   | Salesperson identifier            |
| campaign_sk      | Campaign identifier               |
| sales_date       | Date of transaction               |
| total_amount     | Sales amount                      |

---

### 🔹 Dimension Tables

* **`dim_customers.csv`** → Customer details & segmentation
* **`dim_products.csv`** → Product information
* **`dim_salespersons.csv`** → Salesperson data
* **`dim_stores.csv`** → Store details (type, location, etc.)
* **`dim_campaigns.csv`** → Marketing campaigns
* **`dim_dates.csv`** → Date hierarchy (month, year, etc.)

---

## 🧠 Data Modeling

* Implemented a **star schema** for optimized performance
* Established relationships between fact and dimension tables
* Used surrogate keys for efficient joins
* Ensured normalization to reduce redundancy

---

## 📊 Dashboard Features

### 1️⃣ Key Metrics (KPIs)

* 💰 **Total Sales:** 2.75 Billion
* 👥 **Total Customers:** 100K
* 🔄 **Total Transactions:** 1 Million

---

### 2️⃣ Top Products by Sales

* Highlights highest revenue-generating products
* Enables product-level performance comparison

---

### 3️⃣ Sales Trend Over Time

* Monthly sales visualization
* Helps identify seasonal patterns and growth trends

---

### 4️⃣ Customer Segmentation Analysis

Segments include:

* Online Shoppers
* Deal Seekers
* High Value Customers
* Churn Risk
* Loyal Customers
* First-time Buyers
* Budget Shoppers
* In-store Regulars
* Premium Segment

---

### 5️⃣ Top Salespersons

* Displays top contributors to revenue
* Useful for performance evaluation

---

### 6️⃣ Campaign Budget vs Revenue

* Compares marketing spend vs generated revenue
* Helps measure campaign effectiveness (ROI)

---

### 7️⃣ Sales by Store Type

* Supermarkets
* Small Stores
* Large Malls
* Enables channel performance analysis

---

## 📸 Dashboard Preview

<img width="1301" height="733" alt="Screenshot 2026-03-31 133643" src="https://github.com/user-attachments/assets/1a544966-797e-4f66-a6a7-14568d14db92" />


---


## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **CSV Data Sources**
* **Data Modeling (Star Schema)**
* **DAX (Data Analysis Expressions)**

---

## 📈 Key Insights

* A small set of products contributes significantly to total sales (Pareto effect)
* Seasonal spikes observed in sales trends
* High-value customers contribute disproportionately to revenue
* Some campaigns show high ROI, while others underperform
* Store type impacts sales distribution significantly

---

## 📌 How to Use

1. Open `Sales Dashboard.pbix` in Power BI Desktop
2. Ensure all CSV files are in the correct data source path
3. Refresh data if needed
4. Interact with filters and visuals to explore insights

---

## 🎯 Project Objective

To build a **scalable, insight-driven BI solution** that transforms raw transactional data into meaningful business intelligence for decision-making.

---
