# Pizza_Sales_SQL

🍕 Pizza Sales Analysis Using SQL
📌 Project Overview

This project analyzes pizza sales data using SQL to extract meaningful business insights. The analysis covers order volume, revenue, pizza categories, sizes, sales trends, and customer ordering patterns.

The project is divided into three difficulty levels:

Basic Analysis
Intermediate Analysis
Advanced Analysis

A total of 11 SQL business questions are solved using SQL concepts such as:

JOIN
GROUP BY
Aggregate Functions
CTE
Window Functions
RANK() and DENSE_RANK()
SUM() and AVG()
Date and Time Functions

🎯 Project Objectives:

The main objectives of this project are to:

Analyze the total number of orders placed.
Calculate the total revenue generated from pizza sales.
Identify the highest-priced pizza.
Find the most commonly ordered pizza size.
Identify the top-performing pizza types.
Analyze pizza sales by category.
Understand order distribution throughout the day.
Calculate average daily pizza orders.
Analyze revenue contribution by pizza category.
Calculate cumulative revenue over time.
Identify the top revenue-generating pizzas within each category.
📊 Dataset

The project uses the following tables:

1. orders

Contains information about customer orders.

Column	Description
order_id	Unique order identifier
order_date	Date of the order
order_time	Time when the order was placed
2. order_details

Contains details of pizzas included in each order.

Column	Description
order_details_id	Unique order detail identifier
order_id	Order identifier
pizza_id	Pizza identifier
quantity	Number of pizzas ordered
3. pizzas

Contains pizza information and pricing.

Column	Description
pizza_id	Unique pizza identifier
pizza_type_id	Pizza type identifier
size	Pizza size
price	Pizza price
4. pizza_types

Contains information about pizza names and categories.

Column	Description
pizza_type_id	Unique pizza type identifier
pizza_name	Name of the pizza
category	Pizza category

Files Included:
SQL queries used for analysis (Pizza_Sales_Analysis.sql)
Dataset schema.

Tools Used:
SQL (PostgreSQL)

👨‍💻 Author

Sukesh Kumar Sahoo.

Skills: SQL | PostgreSQL | Data Analysis | Window Functions | CTE | Data Analytics
LinkedIn: www.linkedin.com/in/sukeshkumar1994 
