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
- take top 10 of sum of sale_price column by descending orders

### 2. find top 5 highest selling products in each region




