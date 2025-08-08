# Raleigh Car Crashes: Data Science & Analytics Project

This project analyzes car crash data from Raleigh, North Carolina (2015–2024) to uncover patterns, forecast future crash trends, and predict fatal outcomes. It combines exploratory analysis, time-series forecasting, and classification modeling to support public safety and urban planning. 

---

## Project Highlights

- **Data Cleaning & Feature Engineering**
  - Cleaned and manipulated crash records using `pandas`
  - Engineered temporal features (hour, weekday, month)
  - Encoded categorical variables and handled missing data

- **Exploratory Data Analysis**
  - Visualized crash frequency by time, location, and zone
  - Identified seasonal patterns and high-risk roads
  - Used `matplotlib` and `seaborn` for plots

- **Time-Series Forecasting**
  - Forecasted monthly crash counts for 2025 using:
    - `XGBoost` (feature-based regression)
    - `SARIMA` (statistical seasonal modeling)
  - Compared model outputs and visualized predictions

- **Fatality Prediction**
  - Built classification models to predict fatal crashes using:
    - `Logistic Regression` with class weighting for class imbalance
    - `Random Forest` with hyperparameter tuning via `GridSearchCV` to optimize best parameters (depth, splits, and feature selection)
  - Evaluated performance using precision, recall, ROC-AUC, and PR curves
  - Extracted feature importances to guide future data collection

## Sample Visualizations
### 📈 2025 Crash Forecast (SARIMA)
![SARIMA Forecast](x)
---



