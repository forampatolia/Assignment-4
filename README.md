# Assignment 4: Survival Analysis

This repository contains my work for Assignment 4 of BINF5507, focusing on survival analysis of head and neck cancer patients using clinical data.

# Files

- Scripts/main.ipynb: The Jupyter notebook performing the following steps:

- Data cleaning and preprocessing with careful handling of missing and non-numeric values

- Kaplan-Meier survival curve analysis by treatment groups and tumor stage, with data validation to skip invalid or empty groups

- Log-rank tests to compare survival between groups

- Cox Proportional Hazards regression with multiple covariates

- Validation of proportional hazards assumption

- Random Survival Forest (RSF) modeling

- Permutation-based feature importance for RSF to assess variable impact on survival prediction

# Requirements

To run the notebook, you will need the following Python packages installed:

- pandas

- matplotlib

- lifelines

- scikit-survival (for Random Survival Forest implementation)

- seaborn

- numpy

# Notes

- The clinical dataset includes survival times, event indicators, and covariates such as age, treatment modality, and tumor stage.
- The notebook contains detailed analyses and visualizations addressing the assignment requirements, with improved robustness through added data validation steps in survival curve plotting and enhanced model interpretation using permutation importance.


[forampatolia](https://github.com/forampatolia)