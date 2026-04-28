# 📊 Power BI Sales Dashboard Project

## 📌 Project Overview
This project is an interactive Power BI dashboard designed to analyze sales performance and generate business insights. It helps in understanding revenue trends, profit distribution, product performance, and regional analysis.

The goal of this project is to transform raw sales data into meaningful visual insights for better decision-making.

---

## 🛠 Tools & Technologies Used
- :contentReference[oaicite:0]{index=0}
- Power Query (Data Cleaning & Transformation)
- DAX (Data Analysis Expressions)
- Data Visualization Techniques

---

## 📂 Project Files
- `Dashboard.pbix` → Power BI report file
- `Dashboard.pdf` → Exported dashboard for preview
- `Screenshots/` → Dashboard images
- `README.md` → Project documentation

---

## 📊 Dashboard Features
- KPI Cards (Total Sales, Total Profit, Total Orders, Profit Margin)
- Sales trend analysis over time
- Region-wise performance analysis
- Category and product-level analysis
- Interactive slicers (Date, Region, Category)

---

## 📈 Key Insights
- Identified top-performing products based on sales and profit
- Analyzed region-wise contribution to total revenue
- Observed monthly sales trends and seasonal patterns
- Found areas with low performance for improvement

---

## 🧮 DAX Measures Used
```DAX
Total Sales = SUM(Sales[SalesAmount])

Total Profit = SUM(Sales[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

YTD Sales = TOTALYTD([Total Sales], 'Date'[Date])
