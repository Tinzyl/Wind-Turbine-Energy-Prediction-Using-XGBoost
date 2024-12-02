# 🌬️ Wind Turbine Energy Prediction Using XGBoost ⚡

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-XGBoost-orange.svg)  
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)  

---

## **Project Description** 📜
This project predicts **wind turbine active power output** using XGBoost, leveraging wind speed and temporal data as features. The dataset contains historical turbine performance data, including temperature, wind speed, and power generation metrics.

---

## **Features** ✨
- **Data Preprocessing**:
  - Cleaned dataset by handling missing values and outliers.
  - Engineered features such as `hour`, `day`, `month`, and `wind speed`.
  
- **Visualization**:
  - Analyzed correlations with heatmaps and time-series visualizations.
  - Explored trends in power generation over time.

- **Modeling**:
  - Trained two XGBoost regression models:
    - Model 1: Predicting active power using `WindSpeed`.
    - Model 2: Incorporating temporal features (e.g., `hour`, `day`) for improved accuracy.

- **Evaluation**:
  - Metrics: R², MAE, RMSE, MAPE.
  - Achieved **R² = 0.97** and **MAE = 63.13**.
