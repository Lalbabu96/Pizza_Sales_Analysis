# Pizza Sales Analysis
Overview:
This project analyzes a pizza sales dataset using SQL to uncover key business insights, such as top-selling pizzas, revenue trends, and sales performance by category and city. Built as a hands-on exercise in data analytics, it demonstrates intermediate SQL skills including joins, aggregations, window functions, and subqueries—perfect for aspiring data analysts preparing for real-world dashboards.

Key Features & SQL Skills Demonstrated:
Revenue Analysis: Calculated total sales, average order value, and profit margins using GROUP BY, SUM(), and AVG().
Top Performers: Identified best-selling pizzas and categories with RANK() and DENSE_RANK() window functions.
Trend Insights: Analyzed sales by date, hour, and location using DATE() functions, JOINs across multiple tables (orders,orders_details, pizzas, pizza_types).
Complex Queries: Performed multi-table joins, CTEs for peak hours analysis, and ranking queries for city-wise performance.

Dataset-->
Source: Sample pizza sales data (orders,orders_details, order_items, pizzas, pizza_types tables).
Scope: ~30,000+ orders across 2 years, multiple cities, and pizza varieties.

Queries & Insights-->
Sample highlights:
Top 5 pizzas by quantity sold and revenue.
Monthly sales trends and YoY growth.
Peak sales hours and days for inventory planning.
Category-wise profit analysis.

Tech Stack-->
SQL: MySQL (tested in MySQL Workbench)

What I Learned-->
Optimizing complex joins for large datasets.
Using window functions for ranking and running totals.
Translating business questions into efficient SQL queries—great prep for data analyst interviews!
