# 🍕 Pizza Sales Performance Dashboard (Excel)

## 📌 Objective
This project tracks and visualizes pizza sales performance to uncover revenue drivers, identify peak ordering periods, and analyze product performance. It provides actionable insights for business stakeholders in a pizza store, enabling data-driven decisions on inventory, marketing, and customer engagement.

## 🔧 Tools & Techniques
- **Microsoft Excel for data processing and dashboard creation
- **PivotTables & Calculated Fields** for summarizing KPIs and order-level metrics
- **Excel Charts** including:
  - Bar Charts for best and worst-selling pizzas
  - Line and Area Charts for trend visualization
  - Donut Charts for sales by category and size
  - Funnel Chart for total pizzas sold by category
- **Slicers** to filter by pizza category, product type, and size
- **Data Cleaning** using Find & Replace to convert abbreviations (e.g., “L”, “M”, “XL”) into full size names
- **Custom Formatting** for charts, currency fields, and dashboard layout
- **Data Validation** by comparing Excel outputs with SQL query results to ensure accuracy

## 💡 Dashboard Highlights
- **Key Performance Indicators (KPIs)** prominently displayed:
  - Total Revenue
  - Average Order Value
  - Total Pizzas Sold
  - Total Orders
  - Average Pizzas per Order

- **Best/Worst Selling Products**:
  - Top 5 and Bottom 5 pizzas based on total quantity sold
  - Classic Deluxe and Chicken pizzas identified as top performers
  - Brick Oven and Soppressata pizzas marked as underperformers

- **Sales Distribution by Category and Size**:
  - Donut charts display breakdown by pizza category (e.g., Classic, Chicken)
  - Large-sized pizzas lead all size segments, making up 45% of total sales

- **Interactive Filtering**:
  - All visuals respond to slicers allowing segmentation by product and size
  - Integrated summaries and text boxes highlight key takeaways beside each chart

## 🔍 Key Insights
- **Category Insights**: Classic pizzas generate the most sales and orders (≈26% share)
- **Size Preferences**: Large pizzas dominate with 45% of total sales, followed by medium and regular sizes
- **Product-Level Trends**:
  - Top Sellers: Classic Deluxe and Chicken pizzas are the most popular
  - Low Performers: Brick Oven and Soppressata pizzas show minimal traction, suggesting a review of these offerings

## 📎 Note
The dashboard was built using a raw CSV dataset sourced from Kaggle, processed in Excel. Product sizes and duplicate order IDs were cleaned and standardized before analysis. The final dashboard is fully interactive and suitable for use in operations or executive review.
