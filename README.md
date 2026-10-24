# Exploratory Data Analysis in SQL

## Project Overview

This project uses Microsoft SQL Server to explore a retail sales database and investigate customer demographics, product categories, sales performance, and purchasing behavior.

The analysis examines database structure, summarizes key business metrics, compares revenue across customers and product categories, and identifies high- and low-revenue products.

## Tools & Technologies

- Microsoft SQL Server
- T-SQL
- SQL Server aggregate functions
- Joins and subqueries
- Window functions

## Analysis Performed

### 1. Database Exploration
- Examined available database tables and column metadata.
- Identified distinct customer countries and product categories.

### 2. Date Exploration
- Identified the first and last recorded order dates.
- Calculated the date range of available sales data.
- Examined customer birthdates and age-related measures.

### 3. Measures Exploration
- Calculated total sales and quantity sold.
- Calculated average selling price.
- Examined order, product, and customer counts.
- Combined key business metrics into a single result using `UNION ALL`.

### 4. Magnitude Analysis
- Counted customers by country and gender.
- Counted products by category.
- Calculated average product cost by category.
- Analyzed revenue by product category and customer.
- Compared quantities sold across customer countries.

### 5. Ranking Analysis
- Identified the five highest-revenue product subcategories.
- Ranked products by revenue.
- Identified five low-revenue products.
- Ranked customers by revenue.
- Identified customers with the fewest recorded orders.

## SQL Skills Demonstrated

- Aggregate functions: `SUM`, `AVG`, `COUNT`, `MIN`, and `MAX`
- Filtering and sorting using SQL query clauses
- Grouping and summarizing data
- Joins between fact and dimension tables
- Date functions, including `DATEDIFF`
- Subqueries and `UNION ALL`
- Ranking using the `RANK()` window function
- Database metadata exploration using `INFORMATION_SCHEMA`

## Project Structure

- `scripts/exploratory_data_analysis.sql` — SQL queries used throughout the analysis.
- `README.md` — Project overview, analysis sections, and documentation.

## Project Acknowledgment

If applicable, acknowledge any tutorial, course, or external resource that informed the project.
