# Simulation Notebook

This folder contains a simulation notebook for modeling and analyzing production processes of a retail hiking apparel and equipment company. The goal is to optimize production scheduling, assess resource utilization, and evaluate scenario impacts on KPIs such as on-time delivery, machine utilization, and labor utilization.

## Table of Contents
1.1.0. **Data Preparation**
   - 1.1.1. Import Necessary Libraries
1.2.0. **Load and Validate Input Data**
   - 1.2.1. Load CSV Files
   - 1.2.2. Validate and Clean Data
   - 1.2.3. Merge DataFrames
1.3.0. **Adjust Labor Capacity Calculations**
   - 1.3.1. Define Accurate Labor Capacity
   - 1.3.2. Calculate Machine Capacity
   - 1.3.3. Ensure Time Units and Consistency
1.4.0. **Refine the Production Process Modeling**
   - 1.4.1. Define Production Process with Priority
1.5.0. **Recalculate Utilization Rates**
   - 1.5.1. Correct Utilization Calculations
1.6.0. **Implement Enhanced Simulation with Tweaks**
   - 1.6.1. Define the Main Simulation Function
   - 1.6.2. Update Event Functions
   - 1.6.3. Helper Functions
1.7.0. **Run Simulations for Each Scenario**
1.8.0. **Analyze and Present Results**
   - 1.8.1. Print KPI Results
   - 1.8.2. Visualize Results

## Simulation Type
This notebook uses **Discrete-Event Simulation (DES)** via the SimPy framework to model resources, processes, and events.
