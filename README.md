# AI Predictive Maintenance

## Project Overview
This project focuses on using **Artificial Intelligence and Machine Learning** to predict machine failures based on operational data. Predictive maintenance helps identify potential failures before they occur, reducing unexpected downtime, maintenance costs, and production interruptions.

The project uses the **AI4I 2020 Predictive Maintenance Dataset** to explore machine operating conditions and prepare the data for developing a machine failure prediction model.

## Problem Statement
Unexpected machine failures can lead to production delays, increased maintenance expenses, and reduced operational efficiency. Traditional maintenance approaches may not always detect potential failures early enough.

This project aims to analyze machine sensor data and develop a data-driven approach to predict machine failures before they happen.

## Dataset
The project uses the AI4I 2020 Predictive Maintenance Dataset, which contains **10,000 records and 14 original columns**.

The dataset includes operational measurements such as:

- Air temperature (K)
- Process temperature (K)
- Rotational speed (rpm)
- Torque (Nm)
- Tool wear (min)
- Product quality type (L, M, H)

The target variable is **Machine failure**, which indicates whether a failure occurred.

**Note:** The dataset is synthetic and designed to represent predictive maintenance scenarios.

## Project Objectives
- Understand the dataset structure and its features.
- Perform exploratory data analysis (EDA).
- Identify missing values, duplicate records, and potential outliers.
- Analyze feature distributions and relationships.
- Investigate the imbalance in the machine failure target.
- Prepare the data for machine learning.
- Build and evaluate a machine failure prediction model in subsequent stages.

## Methodology
The project follows these steps:

1. **Data Loading and Inspection:** Examine dataset dimensions, columns, data types, and summary statistics.
2. **Data Quality Analysis:** Check for missing values and duplicate records.
3. **Exploratory Data Analysis:** Visualize feature distributions and analyze relationships between variables.
4. **Data Preparation:** Exclude identifier columns and failure-mode indicators that could cause target leakage.
5. **Class Imbalance Analysis:** Investigate the difference between normal operating records and failure records.
6. **Machine Learning:** Prepare a suitable training and evaluation workflow for predicting machine failures.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab
- Scikit-learn

## Current Progress
The current stage focuses on **exploratory data analysis and data preparation**. Model development and evaluation will follow as the project progresses.

## Expected Outcome
The goal is to develop a machine learning model that can identify operating conditions associated with machine failures and support more proactive maintenance decisions.

## Dataset Source
AI4I 2020 Predictive Maintenance Dataset — UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

## Project Status
In Progress
