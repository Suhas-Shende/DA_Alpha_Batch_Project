# 🛒 E-Commerce Data Analysis

This project focuses on analyzing an e-commerce dataset to uncover business insights and customer behavior patterns. The goal is to clean and analyze the data, visualize trends, and understand factors that affect sales and profit. The project involves data cleaning, exploratory data analysis (EDA), and generating insightful visualizations.

## Project Overview

E-commerce businesses generate vast amounts of data that, when analyzed, can help improve operations, optimize marketing strategies, and enhance customer experience. This analysis aims to uncover key patterns in sales performance, customer preferences, and product popularity.

## 🔍 Objective

The primary goal is to understand **what drives sales and profit** in an e-commerce business. Insights derived can be used to:

- Identify top-selling and most profitable products.
- Analyze sales trends across time, and categories.
- Discover underperforming segments and areas for improvement.
- Assist in strategic decision-making for marketing and inventory.

## Dataset

The dataset used for this project contains detailed information about orders, customers, and products in an e-commerce platform. The columns in the dataset are:

- **Order ID** (object): Unique identifier for each order.
- **Order Date** (datetime): The date the order was placed.
- **Ship Date** (datetime): The date the order was shipped.
- **Ship Mode** (object): The shipping method used.
- **Customer ID** (object): Unique identifier for each customer.
- **Segment** (object): Customer segment (Consumer, Corporate, or Home Office).
- **Product ID** (object): Unique identifier for each product.
- **Category** (object): Category of the product.
- **Sub-Category** (object): Sub-category of the product.
- **Product Name** (object): Name of the product.
- **Sales** (float64): Sales amount.
- **Quantity** (int64): Quantity ordered.
- **Discount** (float64): Discount applied.
- **Profit** (float64): Profit gained.

## 📚 Libraries Used

The following Python libraries were used in the project:

### 🔧 Data Handling & Manipulation
- **pandas**: For data loading, manipulation, and aggregation.
- **numpy**: For numerical operations and handling missing data.

### 📊 Visualization
- **matplotlib**: For basic and custom plotting.
- **seaborn**: For advanced statistical visualizations.

## Data Cleaning

The following data cleaning steps were performed:

- Converted date columns to datetime format.
- Removed duplicates and irrelevant columns.
- Handled missing or zero values appropriately.
- Ensured data types were consistent.

## Exploratory Data Analysis (EDA)

In this phase, the following analyses were conducted:

- Sales and profit trends over time.
- Analysis of sales and profit by category and sub-category.
- Customer segment performance.
- Impact of shipping mode on sales and delivery time.
- Correlation between discount, sales, and profit.

## 📊 Key Analyses & Insights

- **Most Profitable Category**: Technology products contributed the most to profit.
- **Underperforming Segments**: Some sub-categories had high sales but low or negative profit.
- **Discount vs Profit**: High discounts often led to reduced profit, revealing the need for optimized pricing.
- **Shipping Impact**: Same-day and second-class shipping modes performed well, but with differing cost implications.

<!-- ## Streamlit Dashboard

A Streamlit dashboard could be created to visualize insights from the data. Key features of the dashboard may include:

- **Sales KPIs**: Display of total sales, average discount, and total profit.
- **Visualizations**: Interactive charts for time trends, category sales, and state-wise performance.

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-data-analysis.git
   cd ecommerce-data-analysis
