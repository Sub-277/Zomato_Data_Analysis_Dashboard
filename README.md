# 📊 Zomato Sales Data Analysis Dashboard

**Author**: Subarna Paul
**Institute**: BPPIMT
**Dataset Source**: [Kaggle - Zomato Sales Dataset](https://www.kaggle.com/datasets/piyushp073/sales-data-for-zomato-dashboard)

## 📁 Project Overview
This Power BI dashboard presents comprehensive insights into Zomato's sales performance based on a dataset extracted from Kaggle. The focus is on key business metrics like sales trends, customer behavior, and city-wise performance.

## 🔍 Table of Contents
1. Dataset Description
2. Data Cleaning & Transformation
3. Dashboard Features
4. DAX Measures Used
5. Visualizations
6. Conclusion

## 📂 Dataset Description
The dataset contains customer orders and restaurant ratings across various cities, food types, and user demographics. Key attributes include:
* `Order_Date`
* `City`
* `Sales_Amount`
* `User_ID`
* `Rating`
* `Product_Type`
* `Customer_Details` (e.g., Occupation, Marital Status)

## 🔧 Data Cleaning & Transformation
* Renamed columns for clarity.
* Converted data types (e.g., date, numeric).
* Removed null and duplicate values.
* Applied Power Query for filtering and merging.
* Created calculated columns (e.g., month names, profit category).

## 📊 Dashboard Features
The Power BI dashboard is split into two pages:

### Page 1: Sales Overview
* 💰 **Total Sales**
* 💳 **Average Sales Amount per User**
* ⭐ **Average User Rating**
* 🏙 **Top 5 Cities by Sales**
* 📈 **Sales Trend Over Years**
* 👤 **Top Occupations of Customers**

### Page 2: Comparative Insights
* 📉 **YoY Sales Growth**
* 📉 **YoY Avg. Sales Growth**
* 📉 **YoY Avg. Rating Change**
* 🍽 **Sales Comparison: Veg vs Non-Veg**
* 🍜 **Top 5 Cuisines by Sales**
* 💍 **Customer Marital Status Distribution**


## 📐 DAX Measures Used
Key DAX measures and calculated columns:
* `avg_rating`: Average user rating
* `avg_rating_yoy_ytd`: YTD Year-over-Year change in avg rating
* `avg_sales_amt`: Average sales per user
* `avg_sales_amt_yoy_ytd`: YTD YoY change in avg sales
* `sales_amt_yoy_ytd`: YTD YoY growth in total sales
* `total_sale_amount`: Total sales amount
* `user_count`: Unique users count

## 📈 Visualizations
The dashboard uses:
* **Cards** for KPIs
* **Bar Charts** (city, cuisine, occupation)
* **Line Charts** for sales trends
* **Donut Charts** (e.g., marital status)
* **Image-enhanced visuals** for food categories
* **Slicers** for interactive filtering (by city, product type, etc.)

## ✅ Conclusion
* Strong focus on sales-driven KPIs and user behavior.
* Clear identification of top-performing cities and products.
* Strategic DAX usage for time-based comparison.
* Interactivity achieved via slicers and intuitive visuals.
* Web scraping was not performed due to platform limitations.

## 🧠 Insights Derived
* 📈 Best-performing cities in terms of revenue
* 📉 Decrease in avg rating and avg sales YoY
* 🍽 Veg items had slightly higher sales than non-veg
* 👤 Majority users are single students or employees
