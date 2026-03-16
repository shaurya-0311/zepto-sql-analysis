# Zepto Inventory Data Analysis (SQL Project)

## Project Overview

In this project, I analyzed a Zepto grocery inventory dataset using SQL.  
The goal was to explore product pricing, discounts, stock availability, and understand which categories generate the most revenue.

The dataset contains around **3700 product records**, including information such as product category, price, discount percentage, stock quantity, and weight.

---

## Tools Used

- SQL
- MySQL

---

## Dataset

The dataset includes the following fields:

- SKU_ID
- Category
- Name
- MRP
- DiscountPercent
- AvailableQuantity
- DiscountedSellingPrice
- WeightInGms
- OutOfStock
- Quantity

---

## What I Did in This Project

### Data Exploration
I started by exploring the dataset to understand the structure of the data.  
This included checking the total number of records, identifying different product categories, and analyzing how many items were currently out of stock.

### Data Cleaning
Some products had invalid pricing values (such as price = 0).  
These records were identified and removed to ensure the analysis was accurate.  
Prices were also converted from paise to rupees.

### Data Analysis
Using SQL queries, I answered several business-related questions, such as:

- Which products offer the highest discounts?
- Which products have high MRP but are currently out of stock?
- Which categories generate the highest estimated revenue?
- What is the price per gram for different products?
- Which categories have the highest stock levels?

---

## SQL Concepts Used

During this project I used several important SQL concepts including:

- SELECT statements
- GROUP BY
- HAVING
- ORDER BY
- CASE statements
- Aggregate functions such as SUM, AVG, and COUNT
- Data cleaning using UPDATE and DELETE

---

## Files in this Repository

- **zepto_analysis.sql**  
  Contains the full SQL script used for the analysis.

- **zepto_v2.csv**  
  The dataset used in this project.

---

## Author

Shaurya Sharma
