#Health Data Analysis - Predicting Death Rate

Project Overview

This project aims to analyze health-related data collected from various cities across five states to determine factors influencing the death rate. The goal is to identify significant attributes that impact mortality and develop a predictive model to help policymakers take necessary actions.

Dataset

The dataset includes various health and medical statistics such as:

Doctor availability rate

Hospital availability rate

Annual per capita income

Population density

State (categorical data)

Project Workflow

1. Data Preprocessing

Load the dataset and check for missing values.

Handle missing values using mean imputation.

Encode categorical variables using One-Hot Encoding.

Split the dataset into training and testing sets.



2. Exploratory Data Analysis (EDA)

Statistical summary and correlation analysis.

Data visualization using heatmaps and pair plots to understand relationships.



3. Model Building

Train a Multiple Linear Regression model to predict the death rate.

Perform feature selection based on correlation analysis.

Evaluate model performance using RMSE (Root Mean Square Error).



4. Model Evaluation

Compare actual vs. predicted death rates.

Visualize prediction results using KDE plots.

Analyze error patterns to improve model accuracy.

Technologies Used

Python

Pandas & NumPy (Data Manipulation)

Scikit-learn (Machine Learning)

Seaborn & Matplotlib (Data Visualization)

Conclusion

The project successfully identifies key factors contributing to the death rate and provides a predictive model that can assist in making informed decisions for improving public health.
