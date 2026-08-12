# 📊 Sales Dashboard Report

Welcome! This repository contains a user-friendly **Sales Dashboard** for interactive analysis of business performance, built using Microsoft Power BI.

The SALES REPORT Dashboard is an interactive analytics solution built using Microsoft Power BI. Its main goal is to give business leaders and analysts clear, actionable insights into sales performance. 

The dashboard displays key metrics such as profit, sales, and quantity sold through visually engaging cards, maps, and charts.

Users can interact with the dashboard through dynamic filters—exploring sales by time period, location (region, state, city), product category, and customer segment (Consumer, Corporate, Home Office). 

It also includes detailed breakdowns for shipping modes and payment methods, helping users spot trends, peak sales periods, top-performing categories, and regional strengths at a glance.

The project is ideal for anyone looking to monitor sales performance, understand customer preferences, and make informed decisions to improve business outcomes.

---

## 📝 Description

A dynamic dashboard delivering instant access to essential business metrics for actionable insights and informed decision-making.

**Highlights include:**
- 📈 **KPI cards:** Total Profit, Sales Revenue, Quantity Sold, Average Delivery Stats.
- 📅 **Sales Trends:** Month/year performance & seasonality.
- 🗺️ **Geo Analysis:** City-wise sales and profit visualization.
- 👥 **Customer Segments:** Consumer, Corporate, Home Office.
- 🗃️ **Category Analysis:** Office Supplies, Technology, Furniture.
- ✈️ **Shipping Profitability:** Profit by shipping mode and region.
- 💳 **Payment Insights:** Quantity by payment method (Cards, COD, Online) per category.
- 🎛️ **Flexible Filters:** Region, State, City, Category, Sub-category.

**Built with:**  
- Microsoft Power BI for real-time analytics and interactive visuals.

---

## 🧩 Features

- 📊 **Total sales, profit, quantity, and delivery KPIs**
- 🗓️ **Monthly, regional, and segment breakdowns**
- 🖼️ **Data visualizations for actionable business intelligence**
- 🔍 **Drill-down filters for custom analysis**

---

## 📈 Key Metrics

| 📌 Metric                | 🔢 Value  |
|-------------------------|----------|
| 💵 Total Profit         | 175.26K  |
| 📦 Total Quantity       | 22,000   |
| 💰 Total Sales          | 1.57M    |
| 🚚 Avg. Delivery (Sum)  | 23,000   |

---
## 📊 DAX Measures

This repository contains analytical insights and visualizations built on the SuperStore Sales dataset using Power BI. Below is an example DAX measure used in the report to calculate the average delivery time between order date and ship date.

## DAX Measure: AvgDeliveryTime

AvgDeliveryTime =
DATEDIFF(
'SuperStore_Sales_Dataset'[Order Date],
'SuperStore_Sales_Dataset'[Ship Date],
DAY
)

This measure calculates the delivery time in days for each order. You can use it to analyze shipping efficiency across regions, categories, or customer segments.


---

## 🪟 Visualizations

- 📅 **Monthly Sales Trends:** (2019–2020)
- 🗺️ **Sales & Profit by City:** U.S. map overview
- 🍩 **Sales by Segment:** Consumer / Corporate / Home Office
- 📊 **Sales by Category:** Office Supplies / Technology / Furniture
- 🛫 **Profit by Shipping Mode & Region**
- 🧾 **Quantity by Category & Payment Mode**

---

## 🛠️ Technologies Used

- **Microsoft Power BI** (dashboard design, analytics, and visuals)

---

## ▶️ Getting Started

1. **Clone the repository:**
    ```
    git clone https://github.com/yourusername/sales-dashboard-report.git
    ```
2. **Open** the file:
    - `SALES REPORT POWER BI.pbix` in **Microsoft Power BI Desktop**
3. **Interact:** Use slicers and charts for custom analysis.

---

## ⚡ Main Insights

- 🏆 **Technology** leads sales; **Office Supplies** follow.
- 👤 **Consumer Segment** drives the most revenue.
- 🚚 **Standard Class** is the top ship mode; profit varies by region.
- 📈 Highest sales quantities in **August–December**.
- 💳 **Online and Cards** preferred payment options.

---

## 🖼️  Dashboard

- 👤 **This image is a Power BI dashboard report titled "SALES REPORT," providing a comprehensive summary of business sales performance using various data visualizations and KPIs. 
- 🚚 **The dashboard utilizes a dark-themed background with vivid charts and intuitive layouts.

<img width="1266" height="716" alt="SCREENSHOT" src="https://github.com/user-attachments/assets/68ab31e4-36bb-45be-a68a-05ba36fbf8f2" />

---

## 📜 License

Distributed under the **MIT License**.

---

## 🤝 Contributing

Issues and pull requests are very welcome!  
For questions or feedback, open an issue or start a discussion.

---

## 📬 Get in Touch

- 📧 Email: [singhalsahil22@gmail.com](mailto:singhalsahil22@gmail.com)
- 💼 LinkedIn: [Sahil Singhal](https://www.linkedin.com/in/sahil-singhal-2b507823b/)
- 💻 GitHub: [0SAHILl](https://github.com/0SAHILl)

---

## 🏆 Credits

- Dataset sourced from [Kaggle](https://www.kaggle.com/)

---
**Thank you for checking out this project! Contributions, suggestions, and feedback are always welcome. Happy analyzing! 🙌**
