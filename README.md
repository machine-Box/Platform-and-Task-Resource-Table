# Data for Dynamic Weapon-Target Assignment (DWTA) Problem

This repository contains the simulation data used in the paper **"Clustered Meta-learning Gaussian Beetle Optimization for Dynamic Weapon-Target Assignment with Temporal Dependencies"**.

## File Description

| File Name | Description |
|-----------|-------------|
| `Case1_Platforms_Tasks.xlsx` | Small-scale case data (12 platforms, 12 tasks, 4 resource types) |
| `Case2_Platforms_Tasks.xlsx` | Medium-scale case data (30 platforms, 24 tasks, 8 resource types) |
| `Case3_Platforms_Tasks.xlsx` | Large-scale case data (50 platforms, 36 tasks, 8 resource types) |
| `Example_for_convergence_curve.xlsx` | Example convergence curve data for algorithm comparison |

## Data Structure

Each Excel file contains two worksheets:

- **Platforms**: Platform properties including ID, reusable resources vector, non-reusable resources vector, moving speed, and initial location
- **Tasks**: Task properties including ID, reusable resources demand, non-reusable resources demand, duration, and location

## Usage

These datasets are designed for evaluating the performance of CMGBO optimization algorithms on the Dynamic Weapon-Target Assignment (DWTA) problem. The three cases represent increasing complexity to test algorithmic scalability and robustness.

