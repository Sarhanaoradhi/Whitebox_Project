# Whitebox_Project
This repository contains two Jupyter Notebooks that explores regression and classification modeling. The aim is to build, evaluate and interpret models in a transparent way.

## Project Overview

In the notebooks, you will find the following steps:

Data loading and basic exploratory analysis

Pre‑processing of features (including handling missing values, encoding, scaling)

Model training and evaluation on a hold‑out test set

Interpretation of model outputs: coefficients, feature importances, residual analysis, Confusion matrix, accuracy, precision, and discussion of model behavior

Conclusion summarizing findings and suggestions for further work

## Dataset

The notebook loads the dataset (details on source, number of observations and variables are provided in the notebook)

Features include a mix of numeric and categorical variables

Target variables are numerical values in regression and categorical in classification

Pre‑processing tasks address missing values, outliers and feature engineering

## How to Run
1) Clone the repository
git clone https://github.com/Sarhanaoradhi/Whitebox_Regression_Project.git
cd Whitebox_Regression_Project

2) Launch Jupyter Notebook
jupyter notebook Whitebox_Regression_Project.ipynb or 

3) Run the notebook cell by cell.

4) Ensure you have the required libraries installed: pandas, numpy, scikit-learn, matplotlib, seaborn.

5) The notebook is self‑contained: it walks through from data load to interpretation.

## Key Insights

The regression model’s performance metrics (such as R², mean squared error) are reported in the notebook.

Feature contributions are discussed in terms of their impact on the target.

Any noteworthy observations around data quality (outliers, missing values) and how they affect interpretability are included.

## Further Work

Explore more complex interpretable models (e.g. decision paths)

Compare white‑box approaches with black‑box ones (e.g., random forest, boosting) and discuss trade‑offs

Expand feature engineering to improve model fit while maintaining interpretability

Use a different dataset with more insight
