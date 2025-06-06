# 🛍️ Online Retail Insights Dashboard

This project focuses on analyzing online retail transactions to uncover actionable business insights such as peak sales periods, most popular products, and country-wise performance. The analysis was performed using Excel and Power Query, followed by building an interactive dashboard for visualization.

## 📌 Project Objectives
- Identify the best month, day, and time for sales to understand customer purchasing behavior.
- Determine top-selling countries and products to support strategic marketing decisions.
- Build an interactive dashboard for quick and easy business insights.

## 🧹 Data Cleaning & Preparation
- Removed blank rows, errors, and unnecessary columns (StockCode, etc.).
- Transformed InvoiceDate into separate Date and Hour columns.
- Added calculated columns:
    - Total Revenue = UnitPrice * Quantity
    - Day = WEEKDAY(InvoiceDate, 2)
- Used Power Query in Excel to clean and transform data with 172K+ rows.

## 📊 Key Insights
- Best Sales Month: July, with revenue of £36.89M
- Top Country: United Kingdom with £295.58M in total revenue
- Peak Hour: 12 PM, generating the highest hourly sales
- Top Product: "WORLD WAR 2 GLIDERS ASSTD DESIGNS" (23,674 units sold)

## 📈 Tools Used
- Microsoft Excel
- Power Query
- Pivot Tables & Charts
- Data Visualization (Line & Column Charts)
- Dashboard Design

## 📷 Dashboard Preview & Link
![Image](https://github.com/user-attachments/assets/78c03765-a21a-4a5d-b2e6-ced8f3abffbe)

https://1drv.ms/x/s!AgafmXUiAOEGgtpxwcNiDv_pJZF2NA?e=VM1rMA

## Dataset Link {Kaggle}
https://www.kaggle.com/datasets/thedevastator/online-retail-transaction-data

