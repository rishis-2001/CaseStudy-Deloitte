# Retail Data Analysis
## Project Overview
This project analyzes retail data for TechRetail using Azure ADF, Blob Storage, Databricks and Power BI to uncover trends and insights from customer and sales information. The report visualizes critical metrics including total sales, product demand by city, customer demographics, and category contributions. The dataset consists of ~300,000 records split into multiple tables to streamline analysis.

## Objectives
The key objectives of this analysis are:

1. **Data Ingestion**
2. **Data Processing**
3. **Data Storage**
4. **Data Visualization**

## Expected Output
1. **Total Sales per City:** Evaluate sales performance by city.
2. **Total Sales per Quarter per Year:** Track quarterly and yearly sales trends.
3. **Total Products Sold per City:** Understand product demand across cities.
4. **Top 10 Selling Products by City:** Identify the most popular products in different locations.
5. **Customer Demographics and Sales Correlation:** Analyze the relationship between customer demographics and purchasing behavior.
6. **Sales Contribution by Product Category:** Determine how each product category contributes to overall sales.

## Dataset Structure
The dataset was separated into the following tables:

**dimcustomers:** Customer demographics including age, income, gender, and location.
**dimproducts:** Product details such as category, brand, and pricing.
**sales_fact:** Detailed sales transactions including quantity, sales amount, and dates.
**dimdate:** Date table with information on months, quarters, and years for time-based analysis.
