# regression_co2_consumption
Project Title: Vehicle CO2 Emission Prediction Using Regression Models

Description:
This project demonstrates the use of various regression techniques to predict vehicle CO2 emissions based on engine size, cylinder count, and fuel consumption data. Using the FuelConsumption dataset, the project implements:

Simple Linear Regression – modeling the relationship between each individual feature (engine size, cylinders, city fuel consumption) and CO2 emissions.

Multiple Linear Regression – predicting CO2 emissions using multiple features simultaneously for better accuracy.

Polynomial Regression – modeling non-linear relationships by applying polynomial transformations to features, improving prediction performance.

Sklearn Pipeline with Polynomial Features – combining preprocessing (standardization), polynomial transformation, and linear regression into a streamlined pipeline for efficient training and testing.

Key Features:

Data exploration and visualization including correlation heatmaps and feature histograms.

Evaluation metrics: Mean Squared Error (MSE) and R-Squared (R²).

Comparison of regression models to determine the most accurate approach.

Results:

Multiple Linear Regression achieved R² ≈ 0.876

Simple Linear Regression with engine size achieved R² ≈ 0.762

Polynomial Regression (degree=4) achieved R² ≈ 0.942

Sklearn Pipeline with polynomial features achieved R² ≈ 0.914

Technologies Used:

Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn for regression models and pipelines

Usage:
Run the Jupyter notebooks in the following order to reproduce the analysis and results:

SimpleLinearRegression.ipynb

MultipleLinearRegression.ipynb

PolynomialRegression.ipynb

SKlearnPipeline.ipynb
