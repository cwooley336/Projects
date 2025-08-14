# Projects
## Data science and analytics projects with Jupyter notebooks, Power BI Dashboards, and project descriptions included:


## 1) Raleigh Car Crashes: Data Science & Analytics Project

This project analyzes car crash data from Raleigh, North Carolina (2015–2024) to uncover patterns, forecast future crash trends, and predict fatal outcomes. It combines exploratory analysis, time-series forecasting, and machine learning (classification) modeling to support public safety. Additionally, an interactive Power BI dashboard was created to further explore raleigh car crash dynamics. 

---

### Project Description

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

### Sample Visualizations
### 2025 Crash Forecast (SARIMA)
![SARIMA Forecast](https://github.com/cwooley336/Projects/blob/823cf5b563c2f4611648acc2c0061e80ce70806c/raleigh-crashes/SARIMA%20forecasted%20crashes.png)
### Top 10 Roads (Crash Count) 
![Top 10 Roads](https://github.com/cwooley336/Projects/blob/823cf5b563c2f4611648acc2c0061e80ce70806c/raleigh-crashes/top_roads.png)
### Directional Crash Density (Relative to Downtown Raleigh)
![Compass](https://github.com/cwooley336/Projects/blob/823cf5b563c2f4611648acc2c0061e80ce70806c/raleigh-crashes/compass_crashes.png)
---
#### 📄 PDF Snapshots of Power BI Dashboard Interactivity

These static PDFs demonstrate key interactive features of the dashboard:

- [📄 Raleigh Crashes Dashboard (Full PDF)](https://github.com/cwooley336/Projects/blob/303043ad763a8e277c2239caf14b7f753935151c/raleigh-crashes/Raleigh%20Crashes%20Dashboard.pdf)
- [📄 Raleigh Crashes Dashboard – Filtered Example (PDF)](https://github.com/cwooley336/Projects/blob/303043ad763a8e277c2239caf14b7f753935151c/raleigh-crashes/Raleigh%20Crashes%20Dashboard%20Filtered%20Example.pdf)

--- 

## 2) Heart Disease Risk Analysis: 

This project analyzes a clinical dataset containing patient information related to heart disease. It combines exploratory data analysis, unsupervised dimensionality reduction, and supervised machine learning to uncover key features associated with heart disease risk. 

---

### Project Description

- **Exploratory Data Analysis (EDA)**
  - Explored feature distributions and group differences using `pandas`, `matplotlib`, and `seaborn`
  - Compared patients with and without heart disease (`target` = 0 vs 1)
  - Identified potential risk factors through summary statistics and visualizations

- **Unsupervised Dimensionality Reduction**
  - Used `t-SNE` to visualize local clustering and nonlinear separability between heart disease classes.
  - Applied `Principal Component Analysis (PCA)` to reduce dimensionality and interpret feature importance.
  
- **Supervised Classification & Feature Importance**
  - Trained an `XGBoost` classifier to predict heart disease status
  - Evaluated feature importance using Gain to identify top predictors
  - Compared supervised feature importances to unsupervised PCA loadings for interpretability

### Sample Visualizations
### Feature Distributions by Heart Disease Status
![Feature Distributions](https://github.com/cwooley336/Projects/blob/main/heart-disease/feature_distributions.png)

### t-SNE Visualization of Heart Disease Clusters
![t-SNE](https://github.com/cwooley336/Projects/blob/main/heart-disease/tsne_plot.png)

### PCA: PC1 vs PC2 Scatterplot
![PCA Scatter](https://github.com/cwooley336/Projects/blob/main/heart-disease/pca_scatter.png)

### Top 10 Features by XGBoost Gain
![XGBoost Gain](https://github.com/cwooley336/Projects/blob/main/heart-disease/xgboost_gain.png)

---




