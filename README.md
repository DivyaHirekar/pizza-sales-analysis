# 🍕 Pizza Sales Analysis using SQL

## 📑 Table of Contents

- [Description](#-description)
- [Problem Statement](#-problem-statement)
- [Objective](#-objective)
- [Data Fields](#-data-fields)
- [Dataset](#-dataset)
- [Analysis Questions](#-analysis-questions)
- [Business Insights](#-business-insights)
- [SQL Concepts Used](#-sql-concepts-used)
- [Tools Used](#-tools-used)
- [Conclusion](#-conclusion)

---

## 📌 Description

This project focuses on analyzing pizza sales data using SQL to uncover valuable business insights related to sales performance, customer purchasing behavior, product demand, and revenue generation. By leveraging SQL techniques, the project transforms raw transactional data into meaningful insights that support data-driven business decisions.

---

## ❓ Problem Statement

The pizza company records daily sales transactions across multiple relational tables, including customer orders, pizza details, and product information. However, the business lacks a structured reporting system to answer critical business questions regarding revenue, product performance, customer preferences, and sales trends.

This project aims to analyze the sales data using SQL and generate actionable insights that support data-driven decision-making.

---

## 🎯 Objective

The primary objective of this project is to:

- Calculate total revenue generated.
- Identify top-selling pizzas.
- Determine the highest-priced pizza.
- Analyze customer ordering behavior.
- Identify the most popular pizza size.
- Compare category-wise sales performance.
- Discover peak order hours.
- Analyze daily sales trends.
- Rank top-performing pizzas.
- Generate meaningful business insights using SQL.

---

## 🗂️ Data Fields

The dataset consists of four relational tables:

### Orders
- Order ID
- Order Date
- Order Time

### Order Details
- Order Details ID
- Order ID
- Pizza ID
- Quantity

### Pizzas
- Pizza ID
- Pizza Type ID
- Size
- Price

### Pizza Types
- Pizza Type ID
- Pizza Name
- Category
- Ingredients

---

## 📊 Dataset

**Dataset Name:** Pizza Sales Dataset

**Tables Used**
- Orders
- Order Details
- Pizzas
- Pizza Types

---

## 📈 Analysis Questions

- What is the total revenue generated?
- Which pizza generates the highest revenue?
- Which pizza is ordered the most?
- What is the most popular pizza size?
- Which category contributes the highest revenue?
- What are the peak order hours?
- What are the daily sales trends?
- Which are the top 3 pizzas in each category?

---

## 💡 Business Insights

- Identified the highest revenue-generating pizzas.
- Determined customer ordering preferences.
- Analyzed peak business hours.
- Evaluated category-wise revenue contribution.
- Identified top-performing products.
- Generated actionable insights for business growth.

---

## 🛠️ SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- HAVING
- INNER JOIN
- Aggregate Functions
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- RANK()
- DENSE_RANK()

---

## 💻 Tools Used

- MySQL / SQL Server
- GitHub
- VS Code / MySQL Workbench

---

## ✅ Conclusion

This project demonstrates how SQL can be used to transform raw transactional data into meaningful business insights. The analysis highlights revenue trends, customer purchasing behavior, and product performance, enabling data-driven business decisions.
