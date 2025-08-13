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
