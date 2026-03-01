🍕 Pizza Sales Data Analysis (SQL + Excel Dashboard)
📌 Project Overview

This project focuses on analyzing Pizza Sales data using MS SQL Server and Microsoft Excel to generate actionable business insights.

The goal of this project is to evaluate sales performance, identify trends, analyze customer behavior, and design an interactive dashboard to support business decision-making.

🎯 Business Objective

The business wants to analyze key sales metrics and answer the following questions:

What is the total revenue generated?
What is the average order value?
How many total pizzas were sold?
How many total orders were placed?
What is the average number of pizzas per order?
Which days and hours generate maximum sales?
Which pizza categories and sizes contribute the most revenue?
What are the top 5 and bottom 5 performing pizzas?

🛠 Tools & Technologies Used

MS SQL Server
Microsoft Excel
Pivot Tables
Power Query
Data Cleaning & Transformation
KPI Calculations
Data Visualization & Dashboard Design

📂 Dataset Information

The dataset contains the following columns:

Order ID
Order Date
Order Time
Pizza Name
Pizza Category
Pizza Size
Quantity
Total Price

Dataset File:

pizza_sales.csv
📊 Key Performance Indicators (KPIs)
KPI	Value
Total Revenue	$817,860
Average Order Value	$38.31
Total Pizzas Sold	49,574
Total Orders	21,350
Average Pizzas Per Order	2.32

📈 Analysis & Insights

🔹 Daily Sales Trend

Highest orders occur on Friday and Saturday
Weekend evenings generate maximum revenue

🔹 Hourly Sales Trend

Peak hours: 12 PM – 1 PM
Second peak after 4 PM

🔹 Sales by Category

Classic category contributes maximum revenue
Followed by Supreme, Veggie, and Chicken

🔹 Sales by Size

Large size pizzas generate highest sales
Medium size follows
XL contributes least

🔹 Top 5 Best Selling Pizzas

The Classic Deluxe Pizza
The Barbecue Chicken Pizza
The Hawaiian Pizza
The Pepperoni Pizza
The Thai Chicken Pizza

🔹 Bottom 5 Worst Selling Pizzas

The Brie Carre Pizza
The Mediterranean Pizza
The Calabrese Pizza
The Spinach Supreme Pizza
The Soppressata Pizza

🧠 SQL Queries Used

This project includes SQL queries for:

KPI calculations
Daily trend analysis
Hourly trend analysis
Percentage of sales by category

Percentage of sales by size

Top 5 and Bottom 5 sellers

Example:

SELECT SUM(total_price) AS Total_Revenue
FROM pizza_sales;

All queries are available in:
PIZZA SALES SQL QUERIES.pdf

📊 Dashboard Features

KPI Cards
Daily Trend Bar Chart
Hourly Trend Line Chart
Category & Size Pie Charts
Top 5 & Bottom 5 Seller Charts
Month Filter
Interactive Design


🚀 Skills Demonstrated

SQL Aggregation & Grouping

Data Cleaning

Business KPI Analysis

Data Visualization

Dashboard Development

Analytical Thinking

Business Insight Generation
