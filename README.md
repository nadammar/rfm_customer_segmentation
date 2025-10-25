# RFM Customer Segmentation

This repository demonstrates a complete workflow for **customer segmentation using RFM (Recency, Frequency, Monetary) analysis** combined with **machine learning clustering** in PySpark. The focus is on identifying valuable customer segments for marketing and business insights.
# RFM Customer Segmentation

This repository presents a comprehensive workflow for **customer segmentation using RFM (Recency, Frequency, Monetary) analysis** enhanced with **machine learning clustering techniques** in PySpark. The main objective is to identify and understand customer behavior patterns to drive marketing strategies and improve business outcomes.

---

## Project Overview

RFM analysis measures key aspects of customer behavior:

* **Recency**: How recently a customer made a purchase
* **Frequency**: How often a customer makes purchases
* **Monetary**: How much a customer spends

By combining these metrics with clustering algorithms, customers are segmented into four meaningful groups:

* **VIP Customers**: Highly engaged, frequent buyers with high spending
* **Loyal Customers**: Regular buyers with consistent spending and engagement
* **At-Risk / Late Customers**: Previously active customers who haven’t purchased recently
* **Low-Value Customers**: Infrequent buyers with low spending and engagement

Clusters are initially identified with algorithm-generated IDs, which are then mapped to the corresponding segment names based on average RFM values. This ensures the segmentation reflects real customer behavior for actionable insights.

---

## Project Structure

The project is organized for clarity and reproducibility:

* **Data**: Original dataset for analysis
* **Notebooks**: Jupyter notebooks with step-by-step workflow and explanations
* **Scripts**: Optional Python scripts for modular execution
* **Output**: Segmented datasets and visualizations
* **Documentation**: README and additional resources

---

## Key Steps

1. **Data Preparation**: Clean and transform raw data for analysis
2. **RFM Metrics Calculation**: Generate Recency, Frequency, and Monetary values per customer
3. **Feature Scaling**: Standardize metrics for fair clustering
4. **Clustering**: Apply machine learning algorithms (K-Means or Gaussian Mixture) to segment customers
5. **Segment Labeling**: Map cluster IDs to meaningful segment names based on average RFM values
6. **Visualization**: Explore customer segments using informative plots
7. **Results Interpretation**: Leverage segmentation insights for marketing and business strategies

---

## Outcomes

* Actionable customer segmentation based on behavior and spending patterns
* Insights into high-value, loyal, at-risk, and low-value customers
* Visual representations to support business decision-making
* Segmented data ready for integration into marketing campaigns or business intelligence systems

---

## Author

**Your Name** – Data Science / AI Enthusiast
Contact: [Email or LinkedIn]

---

## License

This project is licensed under the MIT License – see the LICENSE file for details.

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

