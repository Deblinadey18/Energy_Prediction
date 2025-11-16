Household Energy Prediction Project
📘 Project Overview

Predict household energy consumption using machine learning. Analyze usage patterns, visualize trends, and build predictive models for forecasting power consumption.

📊 Dataset

Name: Household Power Consumption

Source: UCI Machine Learning Repository

File: household_power_consumption.zip

Contains electric power consumption measurements in one household (2006–2010).

🧹 Data Cleaning (Week 1)

Loaded dataset and replaced missing values with NaN

Removed invalid rows and converted numeric columns to float

Filtered dataset for analysis-ready data

📈 Exploratory Data Analysis & Basic Modeling (Week 2)

Visualized Global Active Power, Voltage, and Sub-Metering

Checked distributions using histograms and boxplots

Built Linear Regression model to predict Global_active_power

Evaluated model using R² and Mean Squared Error (MSE)

⚙️ Feature Engineering & Advanced Modeling (Week 3)

Added features: Hour, Weekday, Rolling Averages (1hr & 24hr)

Trained Random Forest and XGBoost models

Compared actual vs predicted values

Built Streamlit dashboard for interactive visualization and predictions

📂 Files Included

energy_prediction.ipynb – Notebook with preprocessing, analysis, and modeling

household_power_consumption.zip – Raw dataset

🎯 Project Goals

Preprocess and clean household energy data

Perform exploratory analysis to understand energy usage

Engineer features to enhance model performance

Train and evaluate advanced predictive models

Build an interactive dashboard for real-time visualization
