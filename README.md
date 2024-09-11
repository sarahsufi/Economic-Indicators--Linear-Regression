     Global Economic Indicators Analysis


Overview

This project provides an analysis of key economic indicators for multiple countries, offering insights into economic performance and income distribution worldwide. The dataset includes data on GDP per capita, the Gini Index (a measure of income inequality), and Gross Domestic Product (GDP). The project uses Linear Regression to explore the relationship between GDP per capita and income inequality. This is ideal for comparative economic analysis, research on global inequality, and the examination of economic trends across regions.

Dataset Features

Region: The country or region for which the data is recorded.

GDP Per Capita: The average economic output per person, measured in USD.

Gini Index: A measure of income inequality, ranging from 0 (perfect equality) to 1 (maximum inequality).

Gross Domestic Product (GDP): The total value of goods and services produced by a country, measured in USD.
Use Cases

Comparative Economic Analysis: Explore the differences in economic performance across countries and regions.

Global Inequality Research: Analyze the relationship between GDP per capita and income inequality using Linear Regression.
Policy Insights: Provide data-driven insights for policymaking and economic development strategies.
Approach
Data Preprocessing:

Handling Missing Values: Ensure data completeness by addressing missing values.
Normalization: Normalize the dataset for better interpretability and meaningful comparisons across countries.
Exploratory Data Analysis (EDA): Visualize data to identify trends and relationships between indicators.
Linear Regression Analysis:

Objective: Use Linear Regression to predict the Gini Index (income inequality) based on GDP per capita.
Model Training: Train a Linear Regression model to understand how changes in GDP per capita affect income inequality.
Model Evaluation: Assess the performance of the model using metrics like R² and Mean Squared Error (MSE).
Analysis:

Correlation Analysis: Explore the correlation between GDP per capita and the Gini Index to quantify the relationship between economic output and inequality.
Regional Comparisons: Compare economic performance and inequality across different regions (e.g., Europe, Asia, Africa).
Visualization:

Scatter Plots: Visualize the relationship between GDP per capita and income inequality.
Regression Line: Plot the linear regression line to observe the impact of GDP per capita on income inequality.
Bar Charts: Compare GDP and income inequality across various regions.

Libraries Used
Pandas, Numpy: For data preprocessing and manipulation.
Matplotlib, Seaborn: For data visualization and plotting regression results.
Scikit-learn: For implementing Linear Regression and evaluating the model.
Usage

Analyze Data: Run python analyze_economy.py to perform exploratory data analysis and visualize key economic indicators.
Linear Regression: Use python linear_regression.py to train and evaluate a linear regression model that predicts income inequality based on GDP per capita.
Compare Countries: Execute python compare_countries.py to compare regions based on GDP and income inequality metrics.

Author: Sarah Sufi

GitHub: sarahsufi
