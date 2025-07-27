# 🍕 Pizza Sales SQL Project

This project contains SQL queries to analyze pizza sales data using MySQL.

## 📌 Project Overview

The aim of this project is to practice SQL queries and gain insights from a hypothetical pizza sales dataset.

## 🛠️ Tools Used
- MySQL Workbench
- SQL

## 📊 Key Metrics Analyzed

- ✅ Total Orders
- 💰 Total Sales (Revenue)

## 🧾 Sample Queries

```sql
-- Total Orders
SELECT COUNT(order_id) AS Total_Orders FROM pizza_sales;

-- Total Sales
SELECT SUM(total_price) AS Total_Sales FROM pizza_sales;
