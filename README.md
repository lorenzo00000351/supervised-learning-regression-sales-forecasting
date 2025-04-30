# Regression Sales Forecasting

This project focuses on forecasting sales based on historical transactional data. It leverages exploratory data analysis (EDA), time series feature engineering, and regression models to predict future sales accurately. Core ideas include custom time-series feature creation and benchmark comparison.

---

## Notebook Contents

- **Data Loading & Cleaning**
  - Fix date formats
  - Imputation of missing values
- **Exploratory Data Analysis (EDA)**
  - Global sales trends
  - Analysis of top cities and categories
- **Feature Engineering**
  - Time-series feature creation
  - Custom encoding for cities based on historical sales volume
- **Modeling**
  - Train-test split based on chronological order
  - Regression model training and evaluation
- **Prediction**
  - Generation of sales forecasts for future periods

---

## Core Ideas

- **Benchmarking Sales Trends**: Establishing baselines using historical patterns.
- **City-based Cardinal Encoding**: Assigning values to cities based on their relative sales volume to preserve business relevance.
- **Time-Series Feature Engineering**: Deriving lag-based features and temporal patterns to enrich model inputs.

---

## Requirements

Main libraries used:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `xgboost` (if used)

