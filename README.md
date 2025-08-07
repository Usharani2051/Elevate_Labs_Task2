# Elevate_Labs_Task2

Sales Dashboard - Power BI

This repository contains a Power BI Sales Dashboard designed to analyze and visualize key sales metrics for business insights and decision-making.

🧾 About the Project

The Sales Dashboard provides a detailed overview of product sales, customer performance, order trends, and regional distribution. It is built using Power BI and leverages interactive visuals for dynamic data exploration.


📌 Features & KPIs

- Total Sales: $10M
- Total Quantity Sold: 99.1K
- Average Sales per Order: $32.7K
- Total Orders: 307
- Regional performance via map visualization
- Top product lines and top customers
- Deal size analysis (Small, Medium, Large) 

---

 📈 Data Visualization

| Chart Title                            | Description |
|----------------------------------------|-------------|
| **Sales Trend Over Time**           | Line chart showing monthly/quarterly sales trends with seasonal insights. |
| **Top-Performing Sales Regions**    | Filled map highlighting geographical revenue distribution. |
| **Sales by Product Line**           | Bar chart showing sales by product categories like Classic Cars, Vintage Cars, etc. |
| **Top Revenue-Contributing Customers** | Sorted bar chart showing top buyers and their contribution to sales. |
| **Sales Breakdown by Deal Size**    | Donut chart showing revenue split across Small, Medium, and Large deal sizes. |

📍 Tools Used
 - Power BI Desktop
 - Excel / PDF Sales Data
 - Dataset: 'Cleaned_Sales_Data.csv'
 - DAX Measures for KPIs:

DAX

Total Sales = SUM('Sales_Data'[Sales])

Total Orders = DISTINCTCOUNT('Sales_Data'[OrderNumber])

Average Order Value = DIVIDE([Total Sales],[Total Orders],0)


🧠 Key Insights
 - Sales consistently peak in Q4.
 - The USA is the top contributor to global sales.
 - A small set of high-value customers generate the majority of revenue.
 - Product demand is dominated by Classic Cars and Collectibles.

