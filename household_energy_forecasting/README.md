# Household Electricity Demand Forecasting

## Project Overview
This repository contains an original statistical analysis project using the UCI Individual Household Electric Power Consumption dataset. The project forecasts daily household electricity demand using time-series feature engineering and compares machine-learning models against a naïve baseline.

## Research Question
Can recent electricity usage, rolling trends, calendar variables, and appliance-zone shares forecast next-day household electricity demand?

## How to Run
1. Open household_energy_forecasting.ipynb in Jupyter Notebook or JupyterLab.
2. Run all cells from top to bottom.
3. If automatic download fails, download the dataset from the UCI Machine Learning Repository and place household_power_consumption.txt in data/raw/.
4. Use the generated figures and tables to finalise the technical report.

## Methods
- Time-aware missing-value handling
- Daily and hourly aggregation
- Lag and rolling-window feature engineering
- Non-parametric statistical testing
- Naïve baseline, Ridge regression, Random Forest, and Gradient Boosting model comparison
- Residual diagnostics and permutation importance


## References
Dua, D., & Graff, C. (2019). UCI Machine Learning Repository. University of California, Irvine, School of Information and Computer Sciences.
