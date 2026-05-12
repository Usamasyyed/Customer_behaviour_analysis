# 🛍️ Customer Shopping Behavior Analysis

![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-Database-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Python](https://img.shields.io/badge/Python-EDA-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Preprocessing-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Overview

This project analyzes customer shopping behavior to uncover actionable insights about revenue patterns, discount effectiveness, subscription value, and product category performance. The analysis follows a complete data analytics pipeline:

- **Data Loading & Cleaning** (Python/Pandas)
- **Exploratory Data Analysis (EDA)** (Python)
- **SQL Querying** (SQL Server)
- **Interactive Dashboard** (Power BI)
- **Final Report & Presentation**

## 📊 Dataset

**Source:** Customer shopping behavior dataset (CSV format)

**Size:** 3,900 rows, 18 columns

**Key Columns:**

| Column | Description |
|--------|-------------|
| `customer_id` | Unique customer identifier |
| `age` / `age_group` | Customer age and binned category |
| `gender` | Male / Female |
| `item_purchased` | Product name |
| `category` | Product category |
| `purchase_amount` | Transaction value in USD |
| `discount_applied` | Yes/No indicator |
| `subscription_status` | Subscriber vs. Non-subscriber |
| `shipping_type` | Shipping method selected |
| `previous_purchases` | Count of prior transactions |

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python (Pandas, NumPy)** | Data loading, cleaning, preprocessing |
| **Jupyter Notebook (VS Code)** | EDA and analysis |
| **SQL Server (SSMS)** | Data storage and querying |
| **Power BI Desktop** | Interactive dashboard creation |
| **Gamma** | Presentation generation |
| **GitHub** | Version control and project hosting |

## 📋 Project Steps

### 1. Data Loading & Cleaning (Python)

- **Handle missing values in review_rating
- **Create age_group column
- **Map frequency_of_purchases to days
- **Standardize column names

### 2. Exploratory Data Analysis (EDA)
- **Analyzed revenue distribution by gender, age, and category
- **Identified discount usage patterns
- **Examined correlation between subscription status and spending

### 3. SQL Analysis (SQL Server)
- **Created database and loaded cleaned data
- **Ran 10 analytical queries to answer business questions
- **Used window functions, CTEs, and aggregations

### 4. Power BI Dashboard
- **Connected Power BI to SQL Server
- **Created interactive visualizations
- **Added slicers for gender, category, shipping type, and subscription status

### 5. Report & Presentation
- **Compiled findings into a structured report
- **Created presentation using Gamma AI
- **Documented insights and recommendations
