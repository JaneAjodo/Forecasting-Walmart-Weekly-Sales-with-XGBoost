# 🧮 Walmart Weekly Sales Forecasting with XGBoost

This project predicts Walmart's weekly sales using machine learning — specifically **XGBoost Regression**, enhanced with **time-based features**, **lag variables**, and **rolling averages**.

## 📁 Dataset

- **Source:** [Kaggle](https://www.kaggle.com/datasets/yasserh/walmart-dataset)  
- **Features:** Store, Date, Weekly_Sales (target), Temperature, Fuel_Price, CPI, Unemployment, Holiday_Flag

## 🧠 Techniques Used

- Time Series Feature Engineering (Month, Week, Year)
- Lag Features (`Lag_1`) and Rolling Averages (`Rolling_Mean_3`)
- XGBoost Regression Model
- Performance Evaluation with RMSE, MAE, and R² Score

## 📊 Model Performance

| Metric      | Value       |
|-------------|-------------|
| RMSE        | 49,072.74   |
| MAE         | 31,304.72   |
| R² Score    | 0.9841      |


## 📌 Visuals

- 📈 Actual vs Predicted Weekly Sales Plot

Read more on [Medium](https://medium.com/@janeajodo/forecasting-walmart-weekly-sales-with-xgboost-e874157fadc7)



