Household Energy Prediction Project
📘 Project Overview

This project focuses on analyzing and predicting household energy consumption using machine learning. The aim is to understand energy usage patterns, visualize trends, and build predictive models for forecasting power consumption.

Week 1: Data Collection & Cleaning

Tasks Completed:

Downloaded the Household Power Consumption dataset (household_power_consumption.zip) from the UCI Machine Learning Repository.

Extracted and loaded the dataset into Python using Pandas.

Performed data cleaning:

Replaced missing values with NaN

Removed invalid rows

Converted numeric columns to float

Filtered the dataset for specific analysis (e.g., 1st–2nd Feb 2007 for visualization examples).

Objective: Prepare a clean and structured dataset ready for exploratory analysis.

Week 2: Exploratory Data Analysis (EDA) & Basic Modeling

Tasks Completed:

Conducted EDA:

Plotted Global Active Power, Voltage, and Sub-Metering trends over time

Generated histograms and boxplots to identify distribution and outliers

Created correlation heatmaps to study relationships between numeric features

Prepared features for modeling:

Selected numeric columns

Handled missing values

Built a Linear Regression model to predict Global_active_power:

Split dataset into training (80%) and testing (20%)

Evaluated model using R² and Mean Squared Error (MSE)

Visualized predictions vs actual values for better insight

Objective: Gain insights from the data and build a baseline predictive model.

Week 3: Advanced Modeling & Dashboard

Tasks Completed:

Feature Engineering:

Extracted Hour and Weekday from datetime

Calculated rolling averages (1-hour and 24-hour) for smoother trends

Advanced Models:

Trained Random Forest Regressor

Trained XGBoost Regressor

Evaluated model performance using R² and RMSE

Visualization:

Compared actual vs predicted values for both Random Forest and XGBoost

Dashboard:

Built a Streamlit dashboard for interactive visualization

Displayed data preview, histograms, and model predictions

Objective: Implement advanced predictive modeling and provide an interactive tool for visualization and monitoring.

📂 Files Included

energy_prediction.ipynb – Notebook with all preprocessing, analysis, and modeling steps

household_power_consumption.zip – Raw dataset

🚀 Project Goals

Preprocess and clean the household power consumption dataset

Explore and visualize energy usage patterns

Engineer meaningful features to improve predictive performance

Train and evaluate advanced models (Random Forest, XGBoost)

Provide a user-friendly dashboard for real-time energy predictio
