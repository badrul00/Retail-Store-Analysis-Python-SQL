## Introduction


## Kaggle API
1. Generate token on Kaggle personal account to use Kaggle API
2. Place kaggle.json on ~/.kaggle/kaggle.json to use the API

## Retail Store Analysis using Python
1. import libraries : kaggle, zipfile, pandas, sqlalchemy
2. download dataset using kaggle api
3. extract file from zip file
4. read data from the file
5. handle null values
6. rename column names, make them lower case and replace space with underscore
7. create new columns : discount, sale_price, profit
8. convert order date from object data type to datetime
9. drop columns : cost_price, list_price, discount_percent
10. load the data into sql server

## Retail Store SQL Queries
1. create retail store table on sql with correct attributes and length to each column
2. run back the python coding of making connection with sql server. change 'replace' to 'append'

## 5 SQL Question 

### 1. find top 10 highest revenue generating products
1. calculates the total sales for each product.
2. orders the products by their total sales in descending order.
3. returns the top 10 products with the highest sales.

### 2. find top 5 highest selling products in each region
1. calculates the total sales for each product in each region
2. assigns a rank to each product based on its sales within its region
3. filters the results to show only the top 5 products by sales in each region

### 3. find month over month growth comparison for 2022 and 2023 sales eg:jan 2022 vs jan 2023
1. This query will output the total sales for each month in 2022 and 2023, allowing for a direct comparison of sales between corresponding months of the two years.
2. The output will have three columns: order_month, sales_2022, and sales_2023, where each row represents a specific month.

### 4. for which category which month had the highest sales
1. calculates the total sales for each category and month.
2. assigns a rank to each month based on its sales within its category
3. filters the results to show only the month with the highest sales for each category
4. The output will have columns such as category, order_year_month, and sales, where each row represents a specific category and the month with the highest sales for that category.

### 5. which sub category had highest growth by profit in 2023
1. calculates the total sales for each sub-category in 2022 and 2023
2. determines the percentage growth in sales from 2022 to 2023 for each sub-category
3. returns the sub-category with the highest growth percentage
4. The output will include columns such as sub_category, sales_2022, sales_2023, and percentage_growth, where the row represents the sub-category with the highest growth in profit.







