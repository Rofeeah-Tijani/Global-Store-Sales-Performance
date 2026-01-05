## 🌍 Global Store Sales Analytics

A Power BI project analyzing global sales performance, customer behavior, product profitability, and regional trends. The project features an interactive dashboard, structured datasets, and actionable KPIs to support data-driven retail and business decisions.

---
## 🏪 Overview

This project leverages global retail transaction data to uncover insights on sales trends, customer segments, product performance, and regional profitability. By transforming raw sales data into interactive Power BI dashboards, it enables business stakeholders to monitor performance, identify growth opportunities, and optimize sales strategies.

---

## ❗ Problem Statement

-Global retail businesses face challenges such as:

-Identifying top-performing and underperforming products

-Understanding customer purchasing behavior across regions

-Tracking revenue, profit, and discount impact

-Monitoring regional and category-level performance

-Making timely, data-driven decisions in a competitive market

-Without consolidated analytics, insights remain fragmented and reactive.

---

## 🎯 Objectives

Analyze sales, profit, and quantity trends over time

Identify high-value customers and key market segments

Evaluate product and category performance

Compare regional and country-level sales performance

Build an interactive Power BI dashboard for executive insights

---

## 📌 Focus Areas

Sales Performance: Revenue, profit, quantity sold, growth trends

Customer Analytics: Customer segments, purchase behavior, loyalty

Product Analysis: Category and sub-category profitability

Regional Insights: Sales and profit by country, region, and market

Discount Impact: Effect of discounts on revenue and profit

---

## 🌐 Data Sources

| Dataset        | Columns                                                                 | Description                                                                 |
|----------------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| orders.csv     | Order_ID, Order_Date, Ship_Date, Ship_Mode, Customer_ID, Product_ID, Sales, Quantity, Discount, Profit | Transaction-level sales data including revenue, profit, and discounts      |
| customers.csv  | Customer_ID, Customer_Name, Segment, Country, Region, Market            | Customer demographic and segmentation information                           |
| products.csv   | Product_ID, Product_Name, Category, Sub_Category                         | Product hierarchy and classification data                                   |
| geography.csv  | Country, Region, Market                                                  | Geographic mapping for regional analysis                                     |
| calendar.csv   | Date, Year, Quarter, Month, Week                                         | Date dimension table for time-based analysis                                 |

---

## 🛠 Tools Used

-Power BI: Data modeling, visualization, and interactive dashboards

-Excel / CSV: Data preprocessing and storage

-DAX: Custom calculations and KPIs

## 🔧 Methodology

Data Cleaning: Removed duplicates, handled missing values, standardized categories

Data Transformation: Created calculated measures such as Total Sales, Total Profit, Profit Margin

Data Modeling: Established relationships between orders, customers, products, and geography

Visualization: Built dashboards highlighting sales trends, customer insights, and regional performance

Insight Extraction: Identified growth markets, loss-making products, and high-value customers

---

## 📊 Key KPIs & Insights

Sales & Profit Metrics

Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Profit Margin = Total Profit ÷ Total Sales

Average Order Value (AOV) = Total Sales ÷ Number of Orders

Customer Metrics

Customer Lifetime Value (CLV)

Sales by Customer Segment

Repeat vs One-Time Customers

Product Performance

Top & Bottom Products by Profit

Category & Sub-Category Contribution

Discount vs Profit Analysis

Regional Performance

Sales & Profit by Region and Country

Market Growth Trends

High-Revenue vs Low-Profit Regions

---

<img width="1394" height="691" alt="Screenshot (395)" src="https://github.com/user-attachments/assets/5a9c6f22-ef0f-49f9-9b63-f537a119917c" />


🔎 Example Insights

High sales volume does not always correlate with high profitability

Certain discounts negatively impact profit despite increasing sales

Corporate customers generate higher average order values

Some regions show strong revenue growth but declining margins

🖼 Dashboard Features

KPI cards: Sales, profit, margin, orders

Line charts: Monthly and yearly sales trends

Bar charts: Category and sub-category performance

Maps: Sales and profit by country and region

Interactive slicers: Date, region, segment, category

🚀 Conclusion

This project demonstrates how Power BI can transform global retail data into actionable insights, enabling businesses to:

Improve profitability through better product and discount strategies

Identify high-value customers and growth markets

Optimize regional and category-level performance

Make proactive, data-driven business decisions






