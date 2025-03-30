# 📊 iPhone Sales Analysis
COMP3125 Individual Project – Spring 2025  
Author: Martin W Barrettt  
School of Computing and Data Science

## 🔍 Project Overview
This project explores customer purchasing behavior related to iPhone sales. Using data-driven analysis and machine learning techniques, it identifies top-selling products, transaction time trends, customer transaction types, and recurring purchase patterns.

The insights from this analysis can help businesses:
- Tailor marketing campaigns
- Optimize inventory management
- Understand customer purchasing cycles

## 📁 Dataset
The dataset used is `Order_details(masked).csv`, which includes:
- Anonymized customer data
- Product names (e.g., iPhone 13 Pro)
- Purchase timestamps
- Quantity per transaction

### Columns:
- `customer_id`
- `email`
- `product`
- `transaction_date`
- `quantity`

> Note: Data cleaning steps were applied to handle missing values and normalize time fields.

##  Methods Used
- **Descriptive Analysis**: Sales frequency and product breakdown
- **Time Series Analysis**: Hour-of-day transaction trends
- **K-Means Clustering**: Identifying returning customer behavior patterns

## 🛠️ Tools & Libraries
- Python 3.9+
- pandas
- matplotlib / seaborn
- scikit-learn
- statsmodels
- Jupyter Notebook (optional for running cells interactively)

##  Key Findings
- iPhone 13 models were the most popular
- Most transactions occurred between 9 AM and 1 PM
- 82% of purchases involved a single item
- Three distinct customer segments identified by K-Means clustering
