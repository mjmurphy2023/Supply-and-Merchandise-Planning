# Simulation Notebook

This folder contains a simulation notebook for modeling and analyzing production processes of a retail hiking apparel and equipment company. The goal is to optimize production scheduling, assess resource utilization, and evaluate scenario impacts on KPIs such as on-time delivery, machine utilization, and labor utilization.

## Table of Contents
1. Data Preparation
   - Import Libraries
   - Load and Validate Data (CSV files like `sales_orders.csv`, `bom.csv`, etc.)
   - Merge DataFrames for simulation
2. Capacity Calculations
   - Define labor and machine capacity
   - Ensure consistent time units
3. Production Process Modeling
   - Define resources and priorities
   - Implement a production process function
4. Simulation Enhancements
   - Update event functions for machine failures and labor shortages
   - Introduce helper functions for resource management
5. Run Scenarios
   - Base case, increased demand, equipment failure, labor shortages, and order prioritization
6. Results and Analysis
   - Calculate KPIs: On-time delivery, utilization rates, throughput time
   - Visualize results with bar charts

## Simulation Type
This notebook uses **Discrete-Event Simulation (DES)** via the SimPy framework to model resources, processes, and events.
