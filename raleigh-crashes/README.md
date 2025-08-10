# Raleigh Car Crashes: Data Science & Analytics Project

This project analyzes car crash data from Raleigh, North Carolina (2015–2024) to uncover patterns, forecast future crash trends, and predict fatal outcomes. It combines exploratory analysis, time-series forecasting, and machine learning (classification) modeling to support public safety. Additionally, an interactive Power BI dashboard was created to further explore raleigh car crash dynamics. 

---

## Project Description

- **Data Cleaning & Feature Engineering**
  - Cleaned and manipulated crash records using `pandas`
  - Prepared data for Power BI interactive dashboard
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
### 2025 Crash Forecast (SARIMA)
![SARIMA Forecast](https://github.com/cwooley336/Projects/blob/823cf5b563c2f4611648acc2c0061e80ce70806c/raleigh-crashes/SARIMA%20forecasted%20crashes.png)
### Top 10 Roads (Crash Count) 
![Top 10 Roads](https://github.com/cwooley336/Projects/blob/823cf5b563c2f4611648acc2c0061e80ce70806c/raleigh-crashes/top_roads.png)
### Directional Crash Density (Relative to Downtown Raleigh)
![Compass](https://github.com/cwooley336/Projects/blob/823cf5b563c2f4611648acc2c0061e80ce70806c/raleigh-crashes/compass_crashes.png)
---

View the Power BI dashboard as a PDF (without interactivity):  
[Raleigh Crashes Dashboard](https://github.com/cwooley336/Projects/blob/35559e0bd0239052a506901c96fcb5c6db25dfca/raleigh-crashes/Raleigh%20Crashes%20Dashboard.pdf)

## 📊 Dashboard PDF

[View the Raleigh Crashes Dashboard (PDF)](raleigh-crashes/Raleigh%20Crashes%20Dashboard.pdf)

## 📊 Interactive Example PDF

[View the Raleigh Crashes Dashboard (PDF)](raleigh-crashes/Raleigh%20Crashes%20Dashboard%20Filtered%20Example.pdf)

