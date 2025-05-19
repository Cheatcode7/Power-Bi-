# 📊 Power BI Sales Dashboard – Superstore Dataset

This project is a beginner-friendly Power BI dashboard built using the Sample Superstore dataset. It helps visualize key business metrics like Total Sales, Profit, Orders, Profit Margin, and Sales Trends across various categories and regions.

---

## 📁 Dataset
- **Source**: [Sample Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
- **Format**: CSV
- **Fields**: Order ID, Sales, Profit, Category, Region, Sub-Category, Product Name, Order Date, etc.

---

## 📈 Dashboard Overview

### ✅ KPIs (Displayed as Cards)
- **Total Sales** – Sum of all sales (e.g., 2.30M)
- **Total Orders** – Count of unique order IDs
- **Total Profit** – Total profit earned (e.g., 286.4K)
- **Profit Margin** – Profit as a percentage of Sales

### 📊 Visualizations

| Visualization        | Description                                 |
|----------------------|---------------------------------------------|
| **Sales Trends**     | Line chart showing sales over time          |
| **Sales by Category**| Bar chart of sales split by product category|
| **Sales by Region**  | Horizontal bar chart of sales by region     |
| **Top 5 Products**   | Bar chart of top-selling products by sales  |
| **Slicers**          | Filter data by Year, Category, and Region   |

---

## 🛠️ Measures (DAX)
```DAX
Total Sales = SUM('Superstore'[Sales])
Total Profit = SUM('Superstore'[Profit])
Total Orders = DISTINCTCOUNT('Superstore'[Order ID])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
