# Flipkart-Sales-Analysis

📊 Flipkart Sales Analysis – Power BI Project

🔹 Project Title
Flipkart Sales Performance Dashboard

🔹 Project Objective
To analyze Flipkart sales data and uncover insights related to revenue, orders, customer behavior, product performance, and discounts using Power BI.

🔹 Dataset Description
Sample dataset includes:

Order ID

Order Date

Product Category

Sub-Category

Brand

Price

Discount (%)

Final Sale Price

Quantity Sold

Customer Location (State / City)

Payment Mode

Order Status

🔹 KPIs & Metrics
✔ Total Revenue
✔ Total Orders
✔ Average Order Value
✔ Total Discount Given
✔ Total Quantity Sold
✔ Top-Selling Categories
✔ Top Brands by Revenue
✔ Sales Growth (Month-on-Month)

🔹 Dashboard Visuals (Power BI)
📈 Sales Trend (Monthly & Yearly) – Line Chart

📊 Revenue by Category & Sub-Category – Bar Chart

🗺 Sales by State – Map Visualization

🧾 Top 10 Products – Table

💳 Payment Mode Analysis – Donut Chart

🔥 Discount vs Sales Impact – Scatter Plot

📦 Order Status Breakdown – Pie Chart

🔹 Key Insights
Electronics contribute the highest revenue during sales.

High discounts significantly increase order volume.

Metro cities generate maximum sales.

UPI & Credit Cards are the most used payment modes.

Festive months show peak sales growth.

🔹 Tools & Skills Used
Power BI

Power Query (Data Cleaning & Transformation)

DAX (Measures & Calculations)

Data Modeling

Data Visualization & Storytelling

🔹 DAX Measures (Examples)
Total Revenue = SUM('Sales'[Final Sale Price])

Total Orders = DISTINCTCOUNT('Sales'[Order ID])

Average Order Value = 
DIVIDE([Total Revenue], [Total Orders])

Total Discount = SUM('Sales'[Discount Amount])
