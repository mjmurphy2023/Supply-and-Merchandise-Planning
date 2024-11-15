# Supply-and-Merchandise-Planning
End-to-end supply and merchandise planning project for a hiking and equipment retailer. Includes synthetic data generation, SQL database management, demand forecasting, and "What-If" simulations to analyze impacts of demand changes, equipment failure, and labor shortages on inventory and resource utilization. 

## Introduction
Effective supply and merchandise planning is crucial for retail businesses to meet customer demand, optimize inventory levels, and maximize profitability. This project simulates a comprehensive planning process for a hiking and equipment retailer by:

- Generating synthetic data that reflects real-world complexities.
- Setting up a SQL database for efficient data management and querying.
- Performing demand forecasting using time series analysis.
- Running simulations to assess the impact of various scenarios on operations.

This project serves as a valuable resource for understanding supply chain dynamics, demand forecasting techniques, and the use of simulations in operational planning.

---

## Project Structure
The project is organized into the following main folders, each focusing on a specific aspect of the supply and merchandise planning process:

### 1. Synthetic Data Creation
**Folder:** `1. Synthetic Data Creation`

This folder contains scripts and tools used to generate synthetic data for the project, including:

- **Inventory Levels:** Stock quantities, reorder points, safety stock levels.
- **Sales Transactions:** Order details, line items, customer information.
- **Production Schedules:** Manufacturing plans, production quantities, timelines.
- **Supplier and Customer Details:** Contact information, performance metrics.
- **Material Requirements:** Bill of materials, component needs.

The synthetic data mimics real-world retail operations, enabling comprehensive analysis and decision-making without proprietary or confidential information.

---

### 2. SQL Setup and Analysis
**Folder:** `2. SQL-Setup-Analysis`

This folder includes a SQL notebook demonstrating:

- Importing CSV data into Pandas DataFrames.
- Creating a SQLite database and importing the DataFrames as tables.
- Executing SQL queries to extract meaningful insights.

**Key Metrics Analyzed:**
- Top-Selling Products
- Sales by Region and Customer Segment
- Inventory Levels and Reordering Needs
- Supplier Performance Metrics
- Monthly Sales Trends
- Customer Segment Insights

The SQL analysis helps understand the data structure and lays the foundation for further analytical tasks.

---

### 3. Demand Forecasting
**Folder:** `3. Demand Forecasting`

This folder explores approaches to demand forecasting using time series data. It focuses on:

- **Data Preprocessing:**
  - Cleaning and organizing sales data.
- **Building Forecasting Models:**
  - Exponential Smoothing 
  - ARIMA Models
- **Model Evaluation:**
  - Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE).
- **Visualization:**
  - Historical sales trends.

Demand forecasting ensures optimal inventory levels and meets customer demand efficiently.

---

### 4. What-If Scenario Simulation
**Folder:** `4. What-If-Senario-Simulation`

This folder contains a simulation notebook for modeling and analyzing production processes, aiming to:

- **Optimize Production Scheduling:** Efficient allocation of resources.
- **Assess Resource Utilization:**
  - Monitor labor and machine utilization rates.
  - Identify production bottlenecks.
- **Evaluate Scenario Impacts on KPIs:**
  - On-Time Delivery Rate
  - Machine Utilization
  - Labor Utilization
  - Average Throughput Time

**Scenarios Analyzed:**
- Increased Demand: Simulating a surge in customer demand.
- Equipment Failures: Assessing the impact of machine downtimes.
- Labor Shortages: Evaluating reduced labor availability effects.
- Order Prioritization: Prioritizing high-margin or urgent orders.

Simulations provide insights into operational factors and support strategic planning.

---

## What's Next?
This project is ongoing, and there are exciting additions planned for the future. Here's  what's to come:

### Production Planning and Scheduling

  - Develop production schedules in Excel based on demand forecasts.
  - Visualize schedules using Gantt charts.
  - Optimize schedules using Python (Linear Programming).

### Material Requirements Planning (MRP)
  - Implement MRP logic in Python:
    - Calculate net requirements.
    - Schedule planned material orders.
  - Integrate MRP with production schedules.
  - Visualize outputs, including planned order releases.

### Performance Monitoring and KPI Reporting
  - Prepare and consolidate data for Power BI dashboards.
  - Connect data sources from SQL and Excel.
  - Build interactive dashboards to monitor:
    - Inventory levels, production adherence, supplier performance, and key KPIs.
  - Include filtering capabilities and advanced visualizations.




