# Business Requirements Document (BRD)
**Project:** Retail Sales & Customer Insights Dashboard  
**Repo:** retail-sales-insights  
**Author:** Jayesh Bawankule  
**Date:** YYYY-MM-DD

---

## 1. Project Overview
The goal of this project is to analyze retail sales data and build a Business Intelligence dashboard that provides actionable insights on revenue, profit, product performance, customer segments, and regional trends. The dashboard will be used by store managers and business stakeholders to make data-driven merchandising and marketing decisions.


## 2. Background / Problem Statement
Retail management currently lacks a centralized view to answer questions such as:
- Which products and categories drive the most revenue and profit?
- Which regions and customer segments are most profitable?
- How do sales trend month-to-month and which months require promotional focus?
- Are discounts reducing profit margins in specific categories?

This project simulates a BI engagement to provide answers via analysis and an interactive dashboard.

---

## 3. Business Objectives (SMART)
1. Provide an interactive dashboard showing top products, sales by region, and monthly trends within **2 weeks** of starting the analysis.  
2. Identify top 5 product SKUs by sales and top 3 low-margin categories with supporting data.  
3. Recommend at least 3 actionable items (pricing, promotions, region focus) to improve profit margin.

---

## 4. Stakeholders
- **Primary:** Retail Manager, Merchandising Lead  
- **Secondary:** Marketing Manager, Finance Analyst, Data Team (junior)

---

## 5. Scope
**In scope**
- Analyze Superstore-style sales dataset (orders, products, region, customer segment, discount, profit).
- Create KPIs and visualizations: Total Sales, Total Profit, Profit Margin, Top Products, Sales by Region, Monthly Trend.
- Deliver a dashboard screenshot and a short PDF Summary with recommendations.

**Out of scope**
- Live data pipelines / deployment (no scheduled ETL).  
- Integration with company ERP or real-time BI tools.  
- Customer-level PII processing or advanced LTV modelling beyond simple aggregates.

---

## 6. Success Metrics / KPIs
- Total Sales (sum of `Sales`)  
- Total Profit (sum of `Profit`)  
- Profit Margin = (Profit / Sales) * 100  
- Top 5 Products by Sales (by SKU or ProductName)  
- Sales by Region & Customer Segment  
- Mon
