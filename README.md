# Energy Prediction

## 📘 Project Description
This project aims to analyze and predict household energy consumption using machine learning.

## 📊 Dataset
The dataset used is **Household Power Consumption**, which contains measurements of electric power consumption in one household.

- File: `household_power_consumption.txt`
- Source: UCI Machine Learning Repository

## 🧹 Data Cleaning
- Replaced missing values (`?`) with NaN.
- Removed rows with missing values.
- Converted numeric columns to float for modeling.

## ⚙️ Files Included
- `energy_prediction.ipynb`: Notebook with preprocessing, model training, prediction, and visualization.
- `household_power_consumption.txt`: Raw dataset.

## 🚀 Objective
- Preprocess the dataset for machine learning.
- Train a **Linear Regression** model to predict `Global_active_power`.
- Evaluate the model using **R² Score** and **Mean Squared Error**.
- Compare actual vs predicted values.
- Visualize the first 100 predictions vs actual values.

## 📈 Week 2 Highlights
1. Selected numeric columns for modeling.
2. Split dataset into training and testing sets (80% train, 20% test).
3. Trained Linear Regression model on training data.
4. Predicted `Global_active_power` on test data.
5. Evaluated model performance.
6. Plotted actual vs predicted values for visualization.
