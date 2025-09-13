# SQL Sales Data Analysis Project

## Overview
This project demonstrates a complete **SQL data analysis** workflow on a simulated e-commerce sales dataset. The goal was to clean, explore, and analyze the data to uncover actionable business insights that could drive decisions in sales, marketing, and operations.

## Tech Stack
- **Database:** Microsoft SQL Server
- **Language:** SQL
- **Key Skills:** Data Cleaning, Exploratory Data Analysis (EDA), Bulk Insert, CTEs, Window Functions, Aggregation

## Dataset
The dataset contains over 10,000 sales transactions with the following attributes:
- `transaction_id`, `customer_id`, `customer_name`, `customer_age`, `gender`
- `product_id`, `product_name`, `product_category`
- `quantity`, `price`, `payment_mode`
- `purchase_date`, `time_of_purchase`, `status` (e.g., delivered, cancelled, returned)

## Data Cleaning & Preparation
Performed extensive data wrangling to ensure data quality:
- Removed duplicate records using `ROW_NUMBER()` and CTEs.
- Standardized categorical values (e.g., 'Male'/'Female' → 'M'/'F').
- Handled NULL values through deletion and updates.
- Corrected column names and validated data types.

## Key Analysis & Insights
Answered critical business questions using SQL:

- **Top Products:** Identified top 5 best-selling products by quantity.
- **Customer Segmentation:** Found top 5 highest-spending customers.
- **Peak Sales Hours:** Analyzed time-based purchase trends.
- **Revenue by Category:** Discovered highest-grossing product categories.
- **Cancellation Analysis:** Calculated cancellation/return rates by category.
- **Payment Preferences:** Identified most and least popular payment methods.
- **Sales Trends:** Evaluated monthly sales performance.
- **Demographic Trends:** Explored purchasing behavior by age and gender.

## Business Impact
The insights provide a foundation for:
- Optimizing inventory management for high-demand products.
- Designing targeted marketing campaigns for VIP customers.
- Reducing revenue loss by addressing cancellation drivers.
- Improving customer support staffing during peak hours.


## Files
- `sqlproject1.sql` – Complete SQL script
- `README.md` – Project documentation

---
