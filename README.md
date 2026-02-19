# 🛍️ AtliQ Mart – Diwali & Sankranti Promotion Analysis

This project analyzes the performance of promotional campaigns conducted by AtliQ Mart during **Diwali 2023** and **Sankranti 2024**.  

Using SQL for data analysis and Power BI for visualization, the project evaluates campaign effectiveness, identifies high-performing products and stores, and measures incremental sales and revenue impact.

---

## 📌 Introduction

Festive promotions are a major driver of sales in the retail industry. Businesses invest heavily in campaigns during peak seasons like Diwali and Sankranti to attract customers and increase revenue.

The objective of this project is to analyze the performance of these campaigns using structured data from AtliQ Mart’s internal databases and generate actionable insights that can help improve future promotional strategies.

---

## 📂 Data Sources

The analysis was conducted using the following datasets:

- `fact_events` – Promotional transaction details
- `dim_products` – Product information and categories
- `dim_stores` – Store location details
- `sales_summary` – Revenue, incremental revenue (IR), and incremental sold units (ISU)

These tables contain information about product pricing, promotional types, store distribution, and sales performance before and after campaigns.

---

## 🎯 Project Overview

- Extracted and analyzed campaign data using SQL
- Addressed five key business requests
- Evaluated revenue uplift and incremental sales
- Built an interactive Power BI dashboard for visualization
- Generated insights to support better marketing decisions

---

## 📊 Business Requests & SQL Analysis

### 1️⃣ High-Value Products in BOGOF Promotion

**Objective:**  
Identify premium products (base price > 500) that were included in the BOGOF (Buy One Get One Free) promotion.

---

### 2️⃣ Store Presence Overview

**Objective:**  
Analyze how many stores are operating in each city and understand geographical distribution.

---

### 3️⃣ Revenue Before vs After Campaign

**Objective:**  
Compare total revenue generated before and after each promotional campaign to measure overall impact.

---

### 4️⃣ Incremental Sold Quantity (ISU%) – Diwali Campaign

**Objective:**  
Calculate category-wise Incremental Sold Quantity Percentage (ISU%) during the Diwali campaign and rank categories by performance.

---

### 5️⃣ Top 5 Products by Incremental Revenue %

**Objective:**  
Identify the top 5 products across all campaigns based on Incremental Revenue Percentage (IR%).

---

## 📈 Results & Key Insights

The analysis revealed several important findings:

- High-value products were actively included in BOGOF promotions.
- Store distribution varied significantly across cities.
- Festive campaigns generated noticeable revenue uplift.
- Certain categories performed exceptionally well during Diwali.
- A small group of products contributed heavily to incremental revenue growth.

These insights can help optimize future festive campaigns and improve resource allocation.

---

## 🔍 Additional Insights Explored

### 🏬 Store Performance Analysis
- Top 10 stores by Incremental Revenue
- Bottom 10 stores by Incremental Sold Units
- City-wise store performance comparison

### 🎁 Promotion Type Analysis
- Top 2 promotion types by Incremental Revenue
- Bottom 2 promotion types by Incremental Sold Units
- Comparison of discount-based, BOGOF, and cashback promotions
- Identification of the most balanced promotion type

### 📦 Product & Category Analysis
- Categories with highest sales lift
- Products highly responsive to promotions
- Relationship between product category and promotion effectiveness

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

- Revenue comparison (Before vs After)
- Category-wise ISU%
- Top products by IR%
- City and store-level performance
- Promotion type effectiveness

The dashboard enables dynamic filtering and drill-down analysis for better business understanding.

---

## ⚠️ Limitations

One key limitation was related to the BOGOF promotion data. The dataset does not separately capture the quantity of free units given, which may slightly affect the accuracy of incremental calculations for this promotion type.

---

## 🚀 Future Improvements

- Incorporate customer-level data for deeper insights
- Perform region-specific detailed analysis
- Implement predictive models for festive sales forecasting
- Include profitability and margin analysis

---

## 👤 Author

Your Name  
SQL | Power BI | Data Analytics

---

⭐ Feel free to fork or explore the project!
