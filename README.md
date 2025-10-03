# 🛒 Store Sales Forecasting – Regularized Regression

This project is part of my internship journey and represents my fifth project in applied Data Science. The goal is to improve forecasting accuracy using Ridge and Lasso regression while avoiding overfitting through regularization techniques.

📌 Project Overview

Dataset: Kaggle – Store Sales Time Series Forecasting https://www.kaggle.com/competitions/store-sales-time-seriesforecasting
Models implemented:

Linear Regression (baseline)

Ridge Regression (with hyperparameter tuning)

Lasso Regression (with hyperparameter tuning)

Compared model performance using RMSE and MAE.

Extracted and visualized feature importance from Ridge & Lasso.

Forecasted sales and visualized predictions vs. actual values.

🔑 Key Features

Time Series Preprocessing: Created lag features, rolling averages, and added holiday/oil price data.

Regularization: Applied Ridge & Lasso with GridSearchCV and TimeSeriesSplit cross-validation.

Evaluation: Compared Linear, Ridge, and Lasso models with metrics.

Feature Importance: Identified which features matter most for forecasting sales.

Visualization: Plots of predicted vs. actual sales and feature importance charts.
