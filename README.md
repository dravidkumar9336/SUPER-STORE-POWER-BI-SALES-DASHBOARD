# 🏬 Super Store Sales Dashboard

## 📌 Overview
This project presents a comprehensive Sales Analysis Dashboard for a Super Store, built using Power BI. It analyzes sales, quantity, profit, and delivery performance across categories, regions, customer segments, and shipping modes.

## 🎯 Business Problem
Store management lacked a consolidated view of how sales were distributed across categories, regions, payment modes, and customer segments — making it hard to identify top-performing areas and delivery bottlenecks. This dashboard consolidates that data into a single interactive view.

## 🛠️ Tools & Tech Stack
- Power BI — dashboard and visualization
- DAX — calculated measures
- CSV — data source (SuperStore_Sales_Dataset.csv)

## 📊 Dashboard Preview

## 🔑 Key Insights
- Total Sales: 1.57M | Total Quantity Sold: 22K | Total Profit: 175.26K | Avg Delivery Rate: 3.76
- Top category by sales: Office Supplies (0.64M), followed by Technology (0.47M) and Furniture (0.45M)
- Payment mode: COD is the most used (43%), followed by Online (35%) and Cards (22%)
- Customer segment: Consumer segment drives the most sales (48%), followed by Corporate (31%) and Home Office (21%)
- Region-wise sales: West and East are tied as top regions (31% each), followed by Central (24%) and South (15%)
- Shipping mode: Standard Class dominates sales (0.33M), followed by Second Class (0.11M), First Class (0.08M), and Same Day (0.03M)
- Top sub-categories: Phones (0.20M), Chairs (0.18M), and Binders (0.17M) lead in sales

## 📈 DAX Measures Used
```dax
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Quantity = SUM(Orders[Quantity])

Avg Delivery Rate = AVERAGE(Orders[AvgDeliveryRate])
```

## ⚙️ How to Run
1. Import `SuperStore_Sales_Dataset.csv` into Power BI
2. Set up data model relationships (if using multiple tables)
3. Open the dashboard file and refresh the data

