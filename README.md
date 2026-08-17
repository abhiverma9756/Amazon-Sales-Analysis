# 🛒 Amazon Sales Analysis 2025

## 📊 Project Overview

This project performs an end-to-end **Amazon Sales Analysis** using Python to understand sales performance, order trends, product category performance, and key business metrics.

The project follows a complete **Data Analyst workflow**:

> 🧹 Data Cleaning → 🔍 EDA → 📊 Visualization → 💡 Business Insights

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze Amazon sales performance
- Identify top-performing product categories
- Analyze order volume
- Calculate and understand Average Order Value (AOV)
- Compare sales and order performance
- Identify important trends and patterns
- Detect potential outliers
- Generate actionable business insights
- Create meaningful data visualizations

---

## 📁 Dataset

**Dataset:** Amazon Sales 2025 INR Cleaned Dataset

The dataset contains summarized Amazon sales information across different report sections and product categories.

### Dataset Information

- 📌 Records: **189**
- 📌 Columns: **6**
- 📌 Data Format: **CSV**
- 📌 Currency: **INR (₹)**

### Main Columns

| Column | Description |
|---|---|
| `Report_Section` | Type of report/analysis section |
| `Dimension` | Category or analytical dimension |
| `Metric1` | Primary numerical metric |
| `Metric2` | Secondary numerical metric |
| `Metric3` | Additional metric |
| `Metric4` | Additional metric |

---

## 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- 📓 Jupyter Notebook

---

## 🔍 Project Workflow

### 1️⃣ Data Loading

Loaded the CSV dataset using Pandas.

```python
import pandas as pd

df = pd.read_csv("amazon_sales_2025_INR_cleaned.csv")
