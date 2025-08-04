# Advanced Analytics & Optimization: Production Planning and Cost Minimization

## Overview

This repository contains end-to-end solutions for core optimization problems in production coordination and resource allocation. The models demonstrate how linear programming can drive informed, data-backed decisions in manufacturing and facilities management. This exercise is designed as a practical introduction to modern operations research methods.

## 🔧 Tools Used
- Python (Pynamo, Pandas, NumPy)
- Jupyter Notebook for interactive modeling
- Excel (Solver)

## Business Objective

To guide effective resource allocation and cost minimization, this analysis answers:
- **How can an organization maximize profit by optimally coordinating production and advertising across multiple products, subject to capacity and market constraints?**
- **What's the most cost-effective purchase plan for supplies (e.g., fertilizers) needed to meet specific requirements when facing multiple purchase options and constraints?**

By structuring real business goals as mathematical models and solving them with industry-standard optimization software, businesses translate strategy into operational action, control costs, and efficiently meet requirements.

This type of optimization model mirrors real-world tradeoffs businesses face in manufacturing, operations, and supply chain planning.

## What You’ll Find Here

- **BA885-Ex-1-Optimization-Solution.ipynb**  
  Python (Pyomo) notebook for fertilizer purchase plan optimization problem. A clean, reproducible Python implementation for formulating and solving the linear program.

- **BA885-Ex-1-Optimization-Solution.xlsx**  
  Excel (Solver) spreadsheets: both advertising/production planning and fertilizer purchasing. Clear representation of business constraints in mathematical terms.

- **BA885-Ex-1-Report.pdf**  
  Scenario analysis to test the sensitivity of profit outcomes based on resource adjustments, model formulations, and detailed solution summaries. 

## Methods & Analysis

### 1. Coordinating Advertising and Production  
*(Future Bright Company)*

- **Objective**: Maximize manufacturing profit by optimally allocating production (by product and shift type) and advertising expenditures, subject to department capacities, demand, budget, and product-specific promo constraints.
- **Approach**:  
  - Formulated as a linear programming problem, variables represent units produced (regular/overtime) and advertising dollars per lamp type.
  - Incorporated constraints for manufacturing capacity, demand (including effects of advertising), budgets, and spend limits.
  - Solved using Excel Solver, with full sensitivity analysis to interpret marginal values of resources and budget changes.
- **Key Takeaway**:  
  Optimization pinpoints how to allocate scarce production and ad resources for maximum profit, identifies bottlenecks, and quantifies the value of expanding those constraints.

### 2. Fertilizer Cost Minimization  
*(Oxbridge University Quadrangle)*

- **Objective**: Determine cost-minimizing purchase quantities of three fertilizers to meet strict minimum requirements for three minerals (nitrogen, phosphorus, potash).
- **Approach**:  
  - Formulated as a linear program with decision variables for each fertilizer's purchase amounts.
  - Constraints ensure requirements for all minerals are met.
  - Model solved both in Excel and using Python's Pyomo library for reproducibility and cross-platform flexibility.
- **Key Takeaway**:  
  Linear programming yields the minimum-cost mix of input resources, ensuring all business needs are satisfied most efficiently.

## Results

- **Production/Advertising**: Solution delivers a labeled, actionable production plan and advertising spend recommendation, maximizing profit within all operational limits. The approach allows "what-if" analysis on constraints and budgets.
- **Fertilizer Purchasing**: Solution identifies optimal (minimum-cost) fertilizer purchase plan, breaking down total cost and confirming all nutrient requirements are met.

## Business Impact & Interpretation

- These optimization models demonstrate how data and analytics directly support operational and strategic objectives from manufacturing throughput and promotional budgeting to procurement of essential supplies.
- Results facilitate scenario analysis, sensitivity testing, and communications with decision-makers for better-informed, evidence-based management.

## How to Use

1. Explore the Jupyter notebook (`BA885-Ex-1-Optimization-Solution.ipynb`) for step-by-step code and explanation on the fertilizer problem.
2. Review the Excel files for detailed Solver solution construction, sensitivity reports, and production plan analysis.
3. Consult the included PDFs for assignment guidelines and in-depth written interpretations.

### Requirements

- **Python 3.x**
- Libraries: `pyomo`, `cbc` (or any standard linear solver supported by Pyomo), `pandas`  
- Excel (Solver & Open Solver) for spreadsheet models

## Learning & Takeaways

- Translate real-world resource allocation problems into mathematical models.
- Apply linear programming to both manufacturing/procurement and resource mix decision problems.
- Learn supporting software tools in both spreadsheet (Excel Solver) and Python (Pyomo) environments.
- Interpret and communicate optimization results for business impact.

## Project Details

- **Completed:** Fall 2024  
- **Course:** Advanced Analytics II – Applied Optimization (BA885), Boston University MSBA

## 💡 Why This Matters

At the heart of business analytics is the ability to **translate ambiguity into mathematical clarity**. This project reflects the skillset required to tackle real operational questions such as:

- How can we align production goals with cost and resource constraints?
- What’s the most profitable product mix under limited capacity?
- How do resource bottlenecks impact overall business outcomes?

*This exercise showcases my comfort with **formulating and solving optimization problems**, as well as translating analytical solutions into **tangible business impact**: skills that are critical in both **analytics consulting** and **data engineering roles** where scalable, insight-driven systems are key.*
