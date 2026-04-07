# Ecommerce Product Data Analysis

This project performs Exploratory Data Analysis (EDA) on an ecommerce product dataset using Python and Pandas.

The goal is to extract useful insights about product pricing, ratings, and stock availability.

---

## Dataset

The dataset contains information about different ecommerce products.

Columns:

- product → product name
- category → product category
- price → product price
- rating → customer rating
- stock → available inventory

---

## Analysis Performed

### Basic Exploration
- viewed dataset structure
- checked column names
- checked dataset shape
- inspected datatypes

### Price Analysis
- calculated average product price
- identified most expensive product
- identified cheapest product
- filtered premium priced products

### Rating Analysis
- found highest rated products
- identified top 3 rated products
- calculated average rating per category

### Category Insights
- average price per category
- average rating per category
- number of products per category

### Inventory Analysis
- calculated total stock available
- identified low stock products
- found product with minimum stock
- average stock per category

### Filtering Insights
- products priced above average price
- products with rating greater than 4.5
- electronics category products
- fashion products priced above 1000

### Sorting Insights
- top 3 most expensive products
- top 3 highest rated products
- sorted products by stock availability

### Feature Engineering
Created new column:

value_score = rating × price

Used to identify high value products.

---

## Technologies Used

- Python
- Pandas

---

## Skills Demonstrated

- DataFrame creation
- data filtering
- sorting data
- aggregation functions
- groupby analysis
- conditional filtering
- feature engineering
- exploratory data analysis workflow

---

## Example Insight

Electronics category contains highest priced products and highest rated products, indicating strong customer preference for electronic items.

---

## Purpose of Project

This project is part of my learning journey in Data Science and helps strengthen understanding of data analysis using pandas.
