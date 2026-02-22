# Retail-Sales-Forecasting
Machine learning time-series forecasting system that predicts future sales using lag features, rolling averages, and regression modeling.

# Retail Sales Forecasting System

## Overview
This project predicts future sales using historical time-series data.  
The goal is to simulate how businesses forecast demand to optimize inventory, staffing, and operations.

---

## Problem Statement
Companies rely on accurate demand forecasting to:
- avoid stock shortages
- reduce inventory costs
- plan logistics
- improve decision-making

This project builds a machine learning model that learns patterns from past sales and predicts future values.

---

## Dataset
Daily time-series dataset used as simulated retail sales data.

---

## Features Engineered
- Lag features (previous days' sales)
- Rolling averages (trend indicators)
- Time-based sequential splitting

---

## Model Used
Linear Regression

---

## Evaluation Metric
Mean Absolute Error (MAE)

Final MAE:
```
5.20
```

---

## Key Learning Outcomes
- Time-series forecasting fundamentals
- Feature engineering for sequential data
- Detecting and fixing data leakage
- Building realistic ML pipelines

---

## Tech Stack
Python  
Pandas  
Scikit-learn  
Matplotlib  

---

## Future Improvements
- Add seasonality features
- Try advanced models (Random Forest, XGBoost, LSTM)
- Deploy as prediction API

---

## Author
Purva Badekar
