# 🛍️ Customer Purchase EDA

This repository contains an exploratory data analysis (EDA) of customer purchase behavior using Python. The dataset includes customer demographics, product categories, and purchase amounts.

The purpose is to explore how factors like gender, age, and product category influence customer purchasing patterns.

---

## 📌 Objective

Analyze and visualize the distribution and trends in customer purchase data, specifically:

- Understand which age groups and genders spend the most
- Identify top product categories by purchase volume
- Highlight high-value customers

This is a foundational EDA — suitable as a starting point for deeper segmentation, modeling, or dashboarding projects.

---

## 📁 Files

| File                             | Description                                |
|----------------------------------|--------------------------------------------|
| `dataset_customer_purchase.ipynb` | Jupyter notebook with full EDA code        |
| `customer_purchase_data.csv`     | Input dataset (must be in same directory)  |

---

## 📊 Dataset Overview

| Column Name       | Description                         |
|------------------|-------------------------------------|
| `User_ID`         | Unique identifier for each customer |
| `Gender`          | Male / Female                       |
| `Age`             | Categorical age range               |
| `Product_Category`| Product group/category              |
| `Purchase`        | Purchase amount in INR (numeric)    |

- Rows: ~5,500  
- No major missing values  
- Mixed data types (categorical + numerical)

---

## 🔎 Analyses Performed

- Gender distribution count
- Age group distribution count
- Purchase amount histogram
- Purchase amount boxplot (outlier detection)
- Total purchase by:
  - Gender
  - Age
  - Product Category
- Top 10 highest-spending customers (by total purchase)

All visualizations were created using **Seaborn** and **Matplotlib**.

---

## 📈 Libraries Used

```python
pandas
matplotlib
seaborn
