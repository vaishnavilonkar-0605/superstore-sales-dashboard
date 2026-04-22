# 🛒 Superstore Sales Dashboard (Power BI)

An interactive **Power BI dashboard** designed to analyze and visualize retail sales data, helping stakeholders make **data-driven business decisions**.

---

## ⚡ Quick Highlights

* 📊 Analyzed **5,901+ sales records**
* 📈 Built **interactive dashboard with KPIs & filters**
* 🔍 Identified **top-performing regions, categories & segments**
* 💡 Delivered **actionable business insights**
* 🛠️ Used **Power BI, DAX, Power Query**

---

## 💡 Why This Project?

Retail businesses generate massive sales data but often struggle to extract meaningful insights.

This dashboard solves that problem by:

* Providing **clear KPIs**
* Tracking **sales trends over time**
* Highlighting **customer behavior & preferences**

---

## 🎯 Business Objective

* Monitor **Sales, Profit, and Quantity**
* Analyze **Year-over-Year Growth (2019 vs 2020)**
* Identify **top-performing states and categories**
* Understand **payment modes & shipping trends**

---

## 🖥️ Dashboard Preview

### 📄 Sales Overview

<img width="591" height="362" alt="image" src="https://github.com/user-attachments/assets/a4e0d12d-84fa-4365-b77d-057954b3ff3b" />


### 📄 Sales Trend & State Analysis

<img width="592" height="356" alt="image" src="https://github.com/user-attachments/assets/e9e5b856-522f-47be-81b5-a6496b5a63ef" />


---

## 📊 Key Metrics

| Metric            | Value    |
| ----------------- | -------- |
| Total Sales       | $1.57M   |
| Total Profit      | $175.26K |
| Total Quantity    | 22K      |
| Avg Delivery Days | 4 days   |

---

## 📌 Key Insights

* 📈 Sales peaked during **Oct–Dec 2020**
* 📍 **California** generated highest revenue ($0.27M)
* 💳 **Cash on Delivery (43%)** is most preferred payment mode
* 🚚 **Standard Class shipping dominates**
* 🏢 **Office Supplies** drives highest revenue
* 💰 **Technology & Furniture** yield better profit margins
* 👥 **Consumer segment (48%)** contributes the most

---

## 🚀 Business Impact

* Enabled identification of **high-performing regions**
* Helped uncover **customer payment behavior**
* Provided insights to **improve logistics & delivery efficiency**
* Supported **data-driven decision-making**

---

## ⚙️ Key DAX Measures

```DAX
Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Total Quantity = SUM(Quantity)

Avg Delivery Days = 
AVERAGEX(
    Dataset,
    DATEDIFF(Dataset[Order Date], Dataset[Ship Date], DAY)
)

YoY Sales Growth = 
DIVIDE(
    [Sales Current Year] - [Sales Previous Year],
    [Sales Previous Year]
)
```

---

## 📂 Dataset Information

| Property | Details                      |
| -------- | ---------------------------- |
| File     | SuperStore_Sales_Dataset.csv |
| Records  | 5,901                        |
| Period   | 2019–2020                    |
| Region   | United States                |

---

## 🛠️ Tools & Technologies

* **Power BI Desktop** – Data visualization
* **DAX** – KPI calculations
* **Power Query** – Data transformation
* **CSV Dataset** – Source data

---

## 🗂️ Repository Structure

```
superstore-sales-dashboard/
│
├── screenshots/
│   ├── dashboard_overview.png
│   └── dashboard_trend.png
│
├── data/
│   └── SuperStore_Sales_Dataset.csv
│
├── superstore_sales.pbix
└── README.md
```

---

## 👩‍💻 Author

**Vaishnavi Lonkar**
BSc Information Technology | Data Analytics Enthusiast

📧 Email: [vaishnavilonkar0506@gmail.com](mailto:vaishnavilonkar0506@gmail.com)
🔗 LinkedIn: *(Add your link here)*

---

⭐ *If you found this project useful, consider giving it a star!*

