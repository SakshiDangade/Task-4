# 📊 SuperStore Sales Analysis & Forecast Dashboard

## 📝 Overview

This task focuses on analyzing the **SuperStore Sales Dataset** and building an **interactive dashboard** using **Power BI** to uncover key business insights and forecast sales for the next 15 days. This is part of a data visualization and forecasting task for submission.

---

## 🛠️ Tool Used

- **Power BI**: For data cleaning, transformation, dashboard creation, and forecasting.

## 📂 Dataset Information

The dataset used is `SuperStore_Sales_Dataset.csv` which contains historical sales data with columns like:
- Order Date, Ship Mode, Customer Segment, Region
- Category, Sub-Category, Sales, Profit, Quantity
- City, State, and Returns

---

## 🔄 Data Preparation Steps

1. **Imported Dataset** into Power BI via *Get Data*.
2. Clicked on **Transform Data** before loading.
3. Performed the following **Data Cleaning** steps:
   - Changed appropriate **data types** for each column (e.g., dates, numbers).
   - Replaced `#N/A` values in the **Returns** column with **0**.
   - Removed **two columns** with missing or irrelevant data.
4. Clicked **Close & Apply** to load the cleaned data into Power BI for visualization.

---

## 📊 Dashboard Creation

Built a fully interactive dashboard in Power BI with the following visuals:

- **Donut Chart**: Sales by Segment
- **Area Chart**: Monthly Sales & Profit trends
- **Map Visualization**: Sales by State
- **Clustered Bar Chart**: Sales by Sub-Category
- **Slicer**: Region filter to analyze data per region
- **KPIs (Cards)**:
  - Total Sales
  - Total Quantity
  - Average Shipping Days
  - Total Profit

Each visual was designed to help stakeholders quickly understand business performance across categories, locations, and customer segments.

---

## 📈 Sales Forecasting (Next 15 Days)

- Used Power BI's built-in **Forecast** functionality.
- Based on **Order Date** (X-axis) and **Sales** (Y-axis).
- Forecasted **next 15 days of sales** with confidence intervals.
- Helped understand upcoming sales trends and guide inventory/marketing strategies.

---

## 💡 Key Business Insights

- **West Region** has the highest contribution to overall sales.
- **Consumer Segment** generates the highest number of orders.
- **Cash on Delivery** is the most commonly used payment method.
- **Phones, Chairs, and Binders** are top-performing sub-categories.
- **Standard Class** is the most preferred shipping mode.
- Monthly sales showed clear peaks in **festive and year-end months**.
- **Forecast** indicated a potential peak of ₹10.6K in the coming 15 days.

