# SQL Setup and Analysis

This folder contains a SQL notebook that demonstrates how to set up a SQLite database from CSV files and perform data analysis for a retail hiking and equipment company. The notebook includes importing data, database creation, and executing SQL queries to generate actionable business insights.

## Table of Contents and Description

### 1.0 Import CSV Files into Pandas DataFrames
**Description**: Load the synthetic CSV data files into Pandas DataFrames for data manipulation and preparation.

### 1.1 Create a SQLite Database and Import DataFrames
**Description**: Establish a SQLite database and import the Pandas DataFrames as tables within the database.

### 2.0 Load SQL Extension and Connect to Database
**Description**: Utilize SQL extensions within the notebook to enable SQL query execution and connect to the SQLite database.

### 2.1 View Tables
**Description**: List all the tables in the database to confirm successful data import and understand the database schema.

### 3.0 Explore Data and Generate Insights

#### 3.1 Top-Selling Products
**Objective**: Identify the top-selling products based on total units sold to understand product performance.

#### 3.1.1 Sales by Region
**Objective**: Analyze total sales by city and customer segment to pinpoint key markets and customer demographics.

#### 3.1.2 Inventory Levels for Reordering
**Objective**: Determine which stores and warehouses have products below the reorder point, indicating the need for restocking.

#### 3.1.3 Supplier Performance Metrics
**Objective**: Evaluate suppliers based on on-time delivery rates and lead time variability to assess reliability and potential risks.

#### 3.1.4 Monthly Sales by Product Category
**Objective**: Examine net revenue by product category on a monthly basis to identify sales trends and seasonal patterns.

#### 3.1.5 Rolling Monthly Sales by Product Category
**Objective**: Calculate month-over-month sales growth percentages for each product category to detect growth patterns and market dynamics.

#### 3.1.6 Customer Segment Insights
**Objective**: Understand purchasing behavior by analyzing total sales for each product category within different customer segments.

#### 3.1.7 Average Order Value by Product Category and Payment Type
**Objective**: Compute the average order value for retail clients, segmented by product category and payment method, to gauge spending patterns.

#### 3.1.8 Payment Method by Client Type
**Objective**: Analyze the payment methods used by different client types and their corresponding order counts and total sales.

#### 3.1.9 Top 10 Suppliers at Risk for Delays
**Objective**: Identify suppliers most likely to cause delays based on high lead time variability and lower on-time delivery rates.

#### 3.1.10 Top 10 Projected Shortages
**Objective**: Determine which products are expected to have the largest inventory shortages in the upcoming month based on forecasted demand and current inventory.

#### 3.1.11 Upcoming Production Schedules at Risk Due to Material Shortage
**Objective**: Identify production schedules that may be delayed due to insufficient inventory of required components.

#### 3.1.12 Total Expected Incoming Inventory from Purchase Orders
**Objective**: Calculate the quantities of products expected to arrive from pending purchase orders within the next week to plan inventory replenishment.

