# 🚴‍♂️ Adventure Works Cycles - Excel Dashboard
![dasboard perview](https://github.com/Mujahid-max/Adventure-works-Excel/blob/main/Screenshot%202025-02-11%20005020.png?raw=true)
## 📌 Overview
Adventure Works Cycles is a manufacturing company that acquired a small plant in Mexico in the 2000s. This plant manufactures key subcomponents, which are shipped to the Bothell location for final product assembly. In **2001**, it became the **sole manufacturer and distributor** of the touring bicycle product group.
![cycling_gif](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcmExdHc3aTBtbWE1aGNseWxkMTF3djR4bncybzJ3cXh6czR5YTA4dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/d1vaWA1lsbIdy/giphy.gif)
This project presents an **interactive Excel dashboard** showcasing sales performance across different **products, customers, and regions** using **Adventure Works dataset**.
![cycling_gif](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2N3ODVvOWg0cHltZWt0eHJiaW85ZmM2dDJxM2ZqMTkzaG14eGNiZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MuEF1omxpdH7q/giphy.gif)
## 📊 Key Features
- **Yearly Sales Analysis** 📅
- **Sales Breakdown by Product Subcategory** 🚴‍♀️
- **Regional Sales Contribution** 🌎
- **Month-wise Sales Trends** 📈
- **Top 10 Customers by Sales** 🏅
- **Sales Amount vs. Production Cost Analysis** 📊
- **KPI Metrics:** Total Sales, Profit, Number of Orders, and Tax Collected 💰

## 🛠️ Data Processing Steps
1. **Data Preparation:**
   - Merged `fact_internet_sales_new` and `fact_internet_sales` (Union Operation)
   - Created `Customer Full Name` by concatenating First, Middle, and Last Names

2. **Feature Engineering:**
   - Extracted key **date-related fields** from `OrderDateKey`:
     - Year, Month Number, Month Name, Quarter, Year-Month, Weekday, Financial Month, Financial Quarter
   - Calculated **Sales Amount** (Unit Price × Order Quantity × Discount)
   - Calculated **Production Cost** (Unit Cost × Order Quantity)
   - Computed **Profit**

3. **Data Visualization:**
   - **Pivot Table for Year-wise Sales Filtering** 🎯
   - **Bar Chart** - Yearly Sales 📊
   - **Line Chart** - Month-wise Sales Trends 📉
   - **Pie Chart** - Quarter-wise Sales 🍕
   - **Combination Chart** - Sales Amount vs Production Cost 📌
   - Additional **KPI Cards & Charts** for better insights 🚀

## 👨‍💻 Project Contributors
- **Mohammed Mujahaid Raza**
- **Shiva**

## 🔍 Tools & Technologies Used
- **Microsoft Excel** 🟢
- **Pivot Tables & Charts** 📈
- **Data Cleaning & Transformation** 🛠️
- **KPI Dashboard Creation** 📊

## 📥 How to Use
1. Download the Excel file 📂
2. Explore the **interactive filters & charts** 🔄
3. Analyze sales performance across different dimensions 🎯

## 🏆 Outcomes
- Improved decision-making with **interactive visual insights**
- Enhanced data analysis skills using **Excel dashboards**
- Effective **storytelling with data** for business impact

💡 **Looking for feedback & collaboration!** Feel free to connect. 🚀

---
#DataAnalytics #ExcelDashboard #PowerBI #SQL #DataVisualization #AdventureWorks #BusinessIntelligence
