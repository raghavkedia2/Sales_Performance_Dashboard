# 📊 Sales Performance Dashboard using Microsoft Excel

> **An end-to-end Business Analytics project built in Microsoft Excel to analyze sales performance, customer behavior, product profitability, and operational efficiency through an interactive dashboard.**

---

## 📌 Project Overview

This project demonstrates how Microsoft Excel can be used as a Business Intelligence (BI) tool to transform raw sales data into meaningful business insights. The project integrates multiple datasets, performs data cleaning and feature engineering, and presents key business metrics through an interactive dashboard.

The analysis helps identify sales trends, profitable product categories, customer purchasing patterns, and operational performance, enabling data-driven business decisions.

---

## 🎯 Project Objectives

- Clean and prepare raw sales datasets.
- Merge multiple datasets into a master analysis table.
- Perform sales and profitability analysis.
- Build an interactive Excel dashboard.
- Visualize business KPIs using PivotTables and PivotCharts.
- Generate actionable business insights.

---

# 📂 Dataset Information

The project consists of three related datasets.

### Orders Dataset

Contains transactional sales data including:

- Order ID
- Customer ID
- Product ID
- Quantity
- Order Date
- Delivery Date

---

### Customers Dataset

Contains customer information including:

- Customer ID
- Customer Name
- Gender
- City

---

### Products Dataset

Contains product information including:

- Product ID
- Product Name
- Category
- Occasion
- Price (INR)

---

# 🧹 Data Cleaning & Preparation

The following data preparation steps were performed:

- Converted raw datasets into Excel Tables
- Checked for duplicate records
- Validated missing values
- Standardized text formatting
- Verified date consistency
- Validated relationships between datasets
- Merged datasets using **XLOOKUP**
- Created a master analysis table

---

# ⚙️ Feature Engineering

The following business metrics were created:

| Feature | Description |
|----------|-------------|
| Revenue | Quantity × Price |
| Estimated Cost | 70% of Selling Price |
| Profit | Revenue − Estimated Cost |
| Profit Margin (%) | Profit ÷ Revenue |
| Delivery Days | Delivery Date − Order Date |
| Month | Month of Order |
| Month Number | Numeric month for sorting |
| Quarter | Q1–Q4 |
| Year | Order Year |
| Weekday | Day of Week |
| Order Size | High / Medium / Low Value Orders |

---

# 📈 Dashboard KPIs

The dashboard displays:

- 💰 Total Revenue
- 📊 Total Profit
- 📦 Total Orders
- 🛒 Average Order Value
- 📈 Profit Margin (%)
- 🚚 Average Delivery Days

---

# 📊 Business Analysis

The dashboard answers key business questions such as:

### Sales Analysis

- Which occasion generates the highest revenue?
- Which months record the highest sales?
- Which cities contribute the most revenue?
- Which products generate the highest sales?

### Product Analysis

- Best-performing product categories
- Most profitable categories
- Revenue contribution by category

### Customer Analysis

- Revenue by city
- Customer order distribution
- Average order value

### Operational Analysis

- Average delivery time
- Monthly sales trend
- Order size distribution

---

# 📉 Dashboard Features

The interactive dashboard includes:

- Executive KPI Cards
- Revenue by Occasion
- Revenue by Category
- Monthly Sales Trend
- Revenue by City
- Profit by Category
- Top Selling Products
- Order Size Distribution
- Interactive Slicers

---

# 🛠️ Excel Skills Demonstrated

- Excel Tables
- XLOOKUP
- Structured References
- IF Statements
- TEXT Functions
- MONTH & YEAR Functions
- PivotTables
- PivotCharts
- KPI Cards
- Slicers
- Conditional Formatting
- Dashboard Design
- Data Validation
- Business Analysis

---

# 📂 Project Structure

```
Sales-Performance-Dashboard
│
├── Dataset
│   ├── Orders.xlsx
│   ├── Customers.xlsx
│   └── Products.xlsx
│
├── Dashboard
│   └── Sales Performance Dashboard.xlsx
│
├── Images
│   ├── Dashboard.png
│   ├── PivotTables.png
│   └── Workbook.png
│
├── Project_Report.pdf
└── README.md
```

---

# 🔄 Project Workflow

```
Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
Data Validation
    │
    ▼
Data Integration (XLOOKUP)
    │
    ▼
Feature Engineering
    │
    ▼
PivotTables
    │
    ▼
PivotCharts
    │
    ▼
Interactive Dashboard
    │
    ▼
Business Insights
```

---

# 📌 Key Insights

The dashboard enables users to:

- Identify the highest revenue-generating occasions.
- Compare profitability across product categories.
- Monitor monthly sales trends.
- Discover top-performing products.
- Analyze customer demand across cities.
- Track average delivery performance.
- Segment orders into High, Medium, and Low value groups.

---

# 💻 Tools & Technologies

- Microsoft Excel
- PivotTables
- PivotCharts
- XLOOKUP
- Slicers
- Conditional Formatting
- Excel Tables

---

# 🚀 Future Improvements

Potential enhancements include:

- Automating data preparation using Power Query
- Building advanced data models with Power Pivot
- Developing an interactive Power BI dashboard
- Integrating SQL databases
- Implementing sales forecasting models
- Performing customer segmentation using Python or R

---

# 📸 Dashboard Preview





# 👨‍💼 About This Project

This project was developed as part of my analytics portfolio to demonstrate practical Microsoft Excel skills in business analytics, data visualization, and dashboard development. It follows a real-world workflow involving data cleaning, integration, feature engineering, KPI reporting, and interactive dashboard creation.

---

## 👤 Author

**Raghav Kedia**

- 🎓 B.Com. (Hons.), Ramjas College, University of Delhi
- 📚 Commerce Major | Economics Minor
- 📈 Aspiring Actuary (IFOA)

---

## ⭐ If you found this project useful, consider giving it a star!
