Amazon Sales Analysis using SQL
📌 Project Overview

This project analyzes Amazon sales data using SQL to uncover key business insights related to revenue, profit, customers, products, regions, and payment methods.
The goal is to simulate a real-world sales analytics workflow using a structured relational database.

🎯 Objectives

Design a normalized sales database

Analyze overall business performance using KPIs

Identify top-performing products, customers, and regions

Track revenue trends over time (monthly & yearly)

Perform advanced analysis using window functions

🛠️ Tech Stack

Database: MySQL

Language: SQL

Concepts Used:

Joins

Aggregations

Date functions

Window functions

CTEs (Common Table Expressions)

🗂️ Database Schema

The database consists of 4 tables:

customers – customer details

products – product catalog

orders – order-level information

order_details – transactional sales data

Relationships are maintained using primary keys and foreign keys.

📈 Key Analyses Performed
🔹 Overall Business KPIs

Total Revenue

Total Profit

Total Orders

Average Order Value

🔹 Time-Based Revenue Analysis

Monthly revenue trends

Yearly & monthly profit tracking

Revenue growth pattern over time

🔹 Product Performance

Top 10 products by revenue

Category-wise revenue and profit contribution

Product ranking using window functions

🔹 Customer Analysis

Top 10 customers by total spend

Customer contribution to overall revenue

🔹 Regional & Payment Insights

Region-wise revenue and profit distribution

Payment method contribution to revenue

🧠 Advanced SQL Concepts Used

CTE (WITH clause) for modular queries

RANK() window function for product ranking

DATE_FORMAT & EXTRACT for time analysis

Multi-table joins for relational insights

💡 Business Insights

A small set of products and customers contribute a large share of revenue

Certain regions outperform others in both revenue and profit

Payment method preference impacts sales volume

Monthly trends help identify seasonal demand patterns
