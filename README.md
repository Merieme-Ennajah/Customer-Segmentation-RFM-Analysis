# Customer Segmentation using RFM Analysis & K-Means Clustering

## Project Overview

This project performs customer segmentation on an online retail dataset using **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering**.

The goal is to identify valuable customer groups and generate actionable insights for marketing and retention strategies.

An interactive **Power BI dashboard** is included for business visualization.

---

## Dataset

The dataset used is the Online Retail Dataset (UCI Machine Learning Repository).

It contains transactional data from a UK-based online retailer between 2010–2011.

- 541,909 transactions (raw)
- 4,338 unique customers after cleaning

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Power BI

---

## Data Cleaning

The dataset was cleaned by:

- Removing missing Customer IDs
- Removing duplicate transactions
- Removing cancelled invoices
- Filtering invalid quantities and prices
- Creating a `TotalSpend` feature

---

## RFM Methodology

Customers are segmented based on:

- **Recency**: Days since last purchase
- **Frequency**: Number of purchases
- **Monetary**: Total spending

---

## Machine Learning Approach

1. Standardized RFM features
2. Used Elbow Method to determine optimal clusters
3. Applied K-Means clustering (k=4)
4. Interpreted customer segments

---

## Customer Segments

| Segment | Description |
|----------|-------------|
| Champions | High value, frequent, recent customers |
| Loyal Customers | Regular and high spending customers |
| Occasional Customers | Low engagement, moderate value |
| At-Risk Customers | Inactive customers needing reactivation |

---

## Key Business Insights

- Champions generate the highest value but are few in number
- Loyal customers provide stable long-term revenue
- At-Risk customers represent churn risk
- Occasional customers offer upselling opportunities

---

## Power BI Dashboard

An interactive dashboard was built with:

- Customer segmentation overview
- Revenue distribution analysis
- RFM behavioral insights

Screenshots are available in the project folder.
