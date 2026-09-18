# -IDRA-Capstone-Project2026-Retail-Intelligence

This project uses historical Walmart store-sales data to understand how weekly sales vary across stores and over time and to build machine-learning models that predict weekly sales.
The project follows the complete data-science workflow — from collecting and cleaning the data to analysing patterns, building prediction models, comparing their performance, and interpreting the results.

## Project Overview
Retail businesses generate large amounts of sales data. Analysing this information can help identify sales patterns and support better planning and forecasting.
In this project, historical weekly sales data from 45 Walmart stores is analysed. The dataset contains weekly sales along with information such as:
1. Store
2. Date
3. Weekly Sales
4. Holiday Flag
5. Temperature
6. Fuel Price
7. Consumer Price Index (CPI)
8. Unemployment

The main goal is to understand the available sales patterns and determine how well machine-learning models can predict weekly store sales.

## Project Workflow
The project was completed through the following stages:

## 1. Data Understanding
The dataset was explored to understand its structure, variables, time period, and basic statistical characteristics.

## 2. Data Cleaning
The data was checked for missing values, duplicate records, invalid sales values, and unusual observations. The dataset was found to have no missing values or duplicate complete records.

## 3. Exploratory Data Analysis
Charts and statistical analysis were used to study sales distributions, store-level differences, trends over time, monthly patterns, holiday periods, and relationships between sales and other available variables.

## 4. Feature Engineering
Additional time-based features such as year, month, quarter, week of the year, time index, and cyclical seasonal features were created to help the models understand temporal patterns.

## 5. Machine Learning
Several regression models were developed:

Linear Regression
Decision Tree Regression
Random Forest Regression

A historical-sales model using previous sales information was also developed as an additional forecasting experiment.
## 6. Model Evaluation
The models were evaluated on temporally unseen data using:

MAE — Mean Absolute Error
MSE — Mean Squared Error
RMSE — Root Mean Squared Error
R² — Coefficient of Determination

## 7. Results & Interpretation
The models were compared based on their test-set performance, and feature importance and prediction behaviour were analysed to understand which information contributed most to the predictions.

## Key Findings
Weekly sales vary substantially between Walmart stores.
Store identity provides a strong predictive signal for weekly sales.
Holiday weeks show higher average observed sales than non-holiday weeks in this dataset.
The available economic and environmental variables have relatively weak individual linear correlations with weekly sales.
Machine-learning models performed substantially better than a simple mean-sales baseline.
The historical-sales forecasting experiment achieved the lowest test error among the models evaluated in this project.

Note: These findings describe relationships observed in the dataset and should not be interpreted as proof of cause-and-effect relationships.

## Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

This project demonstrates an end-to-end application of Python, exploratory data analysis, feature engineering, regression modelling, and model evaluation to a real-world retail sales dataset.
The project also highlights an important principle in predictive modelling: model performance should be evaluated on previously unseen data rather than only on the data used for training.

## Author
Sukhmanpreet Kaur
B.Tech Computer Science & Engineering
India Data and Research Academy (IDRA): Capstone Project
September 2026
