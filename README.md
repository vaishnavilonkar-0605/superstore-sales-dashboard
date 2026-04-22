🛒 Super Store Sales Dashboard
An interactive Power BI dashboard analyzing retail sales performance across regions, categories, segments, and time periods — covering 2019–2020 sales data for a US-based superstore.


🖥️ Dashboard Preview
Page 1 — Sales Overview
Page 2 — Sales Trend & State-wise Analysis

🎯 Project Objective
This project aims to help retail business stakeholders:

Monitor overall sales, profit, and order quantity performance
Analyze sales trends year-over-year (2019 vs 2020)
Identify top-performing states, categories, and customer segments
Understand customer payment preferences and shipping patterns


📌 Key Metrics & Insights
MetricValueTotal Sales$1.57MTotal Profit$175.26KTotal Quantity Sold22K unitsAverage Delivery Days4 daysTop CategoryOffice Supplies ($0.64M)Top Sub-CategoryPhones ($0.20M)Top StateCalifornia ($0.27M)Top SegmentConsumer (48%)Top Payment ModeCOD (43%)Top Ship ModeStandard Class ($0.33M)

📂 Dashboard Pages
1. Sales Overview

KPI cards: Total Sales, Quantity, Profit, Avg Delivery Days
Sales by Customer Segment (Consumer, Corporate, Home Office)
Sales by Payment Mode (COD, Online, Cards)
Monthly Sales Year-over-Year (2019 vs 2020)
Sales by Category (Office Supplies, Technology, Furniture)
Sales by Ship Mode
Sales by Sub-Category (Top 3: Phones, Chairs, Binders)
Region filter (Central, East, South, West)

2. Sales Trend & State Analysis

Daily Sales trend over time (Jan 2019 – Jan 2021)
Zoomed sales trend with interactive date range slider
State-wise Sales breakdown (all US states)


📊 Dataset
PropertyDetailFileSuperStore_Sales_Dataset.csvRecords5,901 rowsPeriod2019 – 2020RegionUnited StatesColumnsOrder ID, Order Date, Ship Date, Ship Mode, Customer Segment, Region, State, Category, Sub-Category, Product Name, Sales, Quantity, Profit, Returns, Payment Mode

🛠️ Tools & Technologies
ToolUsagePower BI DesktopDashboard development & visualizationDAXCalculated measures (YoY growth, KPIs)Power QueryData cleaning and transformationCSV DatasetSource data (5,901 records)

💡 Key Business Insights

Sales grew significantly in late 2020, with the highest spikes in October–December
California leads all states with $0.27M in sales — nearly double second-place New York ($0.16M)
COD is the most preferred payment mode (43%), suggesting an opportunity to incentivize online payments
Standard Class shipping dominates (0.33M) — express options are underutilized
Office Supplies is the highest revenue category, but Technology and Furniture have higher profit margins
Consumer segment contributes 48% of total sales — a key target for retention strategies


🗂️ Repository Structure
superstore-sales-dashboard/
│
├── screenshots/
│   ├── dashboard_overview.png
│   └── dashboard_trend.png
│
├── data/
│   └── SuperStore_Sales_Dataset.csv
│
├── superstore_sales.pbix          # Power BI project file
└── README.md

👩‍💻 Author
Vaishnavi Lonkar
BSc Information Technology | Data Analytics Enthusiast
📧 vaishnavilonkar0506@gmail.com
🔗 LinkedIn
