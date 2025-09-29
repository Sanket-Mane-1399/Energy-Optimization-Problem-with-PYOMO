# Energy Optimization Problem with Pyomo

This repository contains Jupyter Notebooks that demonstrate energy market optimization problems using **[Pyomo](http://www.pyomo.org/)**, a Python-based optimization modeling library.  
The notebooks explore different bidding zone setups and illustrate how optimization techniques can be applied to electricity market problems.

## Repository Contents

1. **Single Bidding Zone with varying period.ipynb**  
   Models a single bidding zone where demand and supply vary across different time periods.  
   Demonstrates how temporal variability influences market clearing and optimization results.

2. **Single Bidding Zone.ipynb**  
   A simpler version with a single bidding zone and fixed time period.  
   Introduces the fundamental market clearing mechanism using optimization.

3. **Two Bidding Zone with Transmission.ipynb**  
   Extends the model to two interconnected bidding zones with transmission constraints.  
   Explores how cross-border capacity and transmission limits affect energy prices and flows.

## Learning Objectives

- Understand how to formulate energy market problems in Pyomo.  
- Learn how market clearing prices are determined in single and multi-zone systems.  
- Explore the impact of transmission limits and varying demand periods.

## Solvers Used

The optimization models in this repository are solved using the following solvers:

- **Gurobi**  
  A state-of-the-art commercial optimization solver known for high performance in large-scale linear, integer, and quadratic programming problems.  

- **HiGHS (via Pyomo-Appsi interface)**  
  An open-source solver for linear programming (LP), mixed-integer programming (MIP), and quadratic programming (QP), integrated through Pyomo's Appsi plugin.  

Both solvers can be selected within the notebooks, depending on availability and licensing.  
