# Assignment 4: Survival Analysis

This repository contains my work for Assignment 4 of BINF5507, focusing on survival analysis of head and neck cancer patients using clinical data.

# Files

- `Scripts/main.ipynb`: The Jupyter notebook where I perform:
  - Data cleaning and preprocessing
  - Kaplan-Meier survival curve analysis by treatment groups
  - Log-rank tests to compare survival between groups
  - Cox Proportional Hazards regression with multiple covariates
  - Validation of proportional hazards assumption
  - Random Survival Forest modeling and comparison

# Requirements

To run the notebook, you will need the following Python packages installed:

- pandas
- matplotlib
- lifelines
- scikit-survival (if RSF is implemented)

# Notes

- The clinical dataset includes survival times, event indicators, and covariates such as age, treatment, and tumor stage.
- The notebook contains detailed analysis and visualizations to address the assignment requirements.

[forampatolia](https://github.com/forampatolia)