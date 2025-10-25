# RFM Customer Segmentation

This repository demonstrates a complete workflow for **customer segmentation using RFM (Recency, Frequency, Monetary) analysis** combined with **machine learning clustering** in PySpark. The focus is on identifying valuable customer segments for marketing and business insights.

---

## Project Overview

RFM analysis evaluates customer behavior:

* **Recency**: How recently a customer made a purchase
* **Frequency**: How often a customer makes purchases
* **Monetary**: How much a customer spends

Based on these metrics, customers are segmented into four main groups:

* **VIP Customers**: High recency, high frequency, and high monetary value
* **Loyal Customers**: Moderate/high frequency, moderate monetary value, recent purchases
* **At-Risk / Late Customers**: Low recency (haven’t purchased recently) with moderate frequency/monetary value
* **Low-Value Customers**: Low on all RFM metrics, less engaged and less valuable



---

## Key Steps

1. **Data Preparation**: Cleaning and transforming raw data for analysis
2. **RFM Metrics Calculation**: Compute Recency, Frequency, and Monetary values for each customer
3. **Feature Scaling**: Standardize metrics to ensure fair clustering
4. **Clustering**: Apply machine learning algorithms (K-Means) to segment customers
5. **Visualization**: Explore customer segments with clear plots
6. **Results Interpretation**: Use segmentation to inform marketing and business strategies

---

## Outcomes

* Clearly defined customer segments based on purchase behavior
* Insights into high-value, loyal, at-risk, and low-value customers
* Visual representations of segments to aid decision-making

---

## Author

**Nada Ammar** – AI & Data Science Engineer

