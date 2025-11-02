# E-commerce-Analytics-Dashboard-Power-BI

This Power BI project offers a comprehensive analysis of e-commerce business performance, enabling stakeholders to track sales, customer behaviour, profit trends, and product performance.

---

## 🚀 Project Overview

This dashboard delivers actionable insights for decision-making across:

- 📦 **Order & Shipping Analysis**
- 🛍️ **Product Category Insights**
- 👥 **Customer Demographics & Segmentation**
- 💰 **Sales & Profitability Trends**
- 🕒 **Monthly Performance Tracking**
- 🌍 **Region-wise Revenue Visualization**

---

## 📂 Files in Repository

| File | Description |
|------|-------------|
| `E-Commerce Analytics Dashboard.pbix` | Power BI report file |
| `data/` | Source dataset (CSV/Excel/SQL export) |

---

## 📁 Data Source

Dataset used: **Sample - Superstore**  
Format: CSV/Excel  
(If using a public dataset, add the link here)

---

## 🧠 Key Features

- 📈 Interactive KPI Cards  
- 🔄 Filters / Slicers (Category, Region, Customer, Date)
- 🕹️ RESET Button
- 📊 Visuals: Line Chart, Bar Chart, Donut Chart, Table, etc
- 🧮 DAX Measures for Calculation

---

## 🧩 DAX Measures/Columns Used

DimDate = CALENDAR(MIN(Orders[Order Date]), MAX(Orders[Order Date]))
Yr-Month = FORMAT(DimDate[Date] , "YYYY-MMM")
Left few char = LEFT(Orders[Product Name], 13)  
Manager2 = RELATED(People[Person])

----

🔧 Tools & Tech Used

1. Microsoft Power BI

2. Power Query

3. DAX

4. Data Modelling (Star Schema)

✅ Output Benefits

✔️ Understand business performance
✔️ Identify high-value customers & products
✔️ Track profit & sales trends over time
✔️ Support marketing & inventory planning

---

🧑‍💻 Author

Vishal jadhav
📧 Email: Jadhavvishal7044@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/vishal-jadhav-895886212/
