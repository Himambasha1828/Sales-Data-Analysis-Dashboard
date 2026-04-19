<<<<<<< HEAD

# Sales Data Analysis and Dashboard Creation

## 📊 Project Overview

This project involves analyzing retail sales data to uncover trends, customer behavior, and performance insights. The analysis was performed using **Python, SQL, and Excel**, while interactive dashboards were created in **Power BI and Tableau** to visualize key business metrics and support decision-making.

---

## 🎯 Objectives

- Analyze product-wise, category-wise, and region-wise sales performance  
- Understand customer buying patterns and seasonal trends  
- Build interactive dashboards for real-time tracking  
- Provide data-driven recommendations for inventory and marketing improvements  

---

## 🛠️ Tools & Technologies

| Tool        | Usage                                |
|-------------|--------------------------------------|
| **Python** (Pandas, Matplotlib, Seaborn) | Data cleaning, transformation, visualization |
| **SQL**     | Extracting insights from structured databases |
| **Excel**   | Preliminary exploration and formatting |
| **Power BI** & **Tableau** | Dashboard creation and KPI visualization |

---

## 📌 Key Insights

- ✅ Identified top-performing and underperforming products  
- 📈 Found strong **seasonal sales patterns**  
- 🌍 Segmented customer behavior by **location and time**  
- 📦 Recommended **inventory optimization** and targeted **promotions**  

---

## 📁 Project Structure

Retail-Sales-Analysis/
├── README.md
├── data/
│ └── sample_sales_data.csv
├── notebooks/
│ └── sales_analysis.ipynb
├── SQL/
│ └── sales_queries.sql
├── dashboards/
│ ├── powerbi_dashboard.png
│ └── tableau_dashboard.png 


---

## 🧾 SQL File: `SQL/sales_queries.sql`

```sql
-- Total sales by category
SELECT Category, SUM(TotalPrice) AS TotalSales
FROM Sales
GROUP BY Category
ORDER BY TotalSales DESC;

-- Top 5 regions by revenue
SELECT Region, SUM(TotalPrice) AS Revenue
FROM Sales
GROUP BY Region
ORDER BY Revenue DESC
LIMIT 5;

-- Monthly sales trend
SELECT DATE_FORMAT(Date, '%Y-%m') AS Month, SUM(TotalPrice) AS MonthlySales
FROM Sales
GROUP BY Month
ORDER BY Month;

-- Top 10 products by sales
SELECT Product, SUM(TotalPrice) AS ProductSales
FROM Sales
GROUP BY Product
ORDER BY ProductSales DESC
LIMIT 10;

## 📊 Dashboard Samples

| Tool       | Screenshot Preview |
|------------|--------------------|
| Power BI   | ![Power BI Dashboard](dashboards/powerbi_dashboard.png) |
| Tableau    | ![Tableau Dashboard](dashboards/tableau_dashboard.png)  |

## 🚀 Project Outcome

This end-to-end project helped develop hands-on experience in:

- Cleaning and analyzing large datasets using Python  
- Writing optimized SQL queries for reporting  
- Creating **interactive dashboards** using Power BI and Tableau  
- Presenting actionable business insights for data-driven decisions  

✅ **Project Type**: Personal / Portfolio  
🗂 **Domain**: Sales & Retail Analytics  
👨‍💻 **Status**: Completed



=======
# Sales-Data-Analysis-Dashboard
>>>>>>> 424f5e06729bc36fc9bd0cfab8f0f2ef44c092eb
