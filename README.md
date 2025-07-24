# 🍏 Apple Stock Price Forecasting using ARIMA & SARIMA

## 📌 Project Overview
This project involves building and comparing ARIMA and SARIMA models for forecasting Apple (AAPL) stock prices. The focus is to evaluate model performance using standard error metrics.

## 📂 Dataset
- **Source**: Kaggle
- **Data**: Apple historical stock prices (including Open, Close, High, Low, Volume, etc.)

## 🧠 Methods Used
- **Exploratory Data Analysis**
- **Stationarity Testing (ADF Test)**
- **Time Series Decomposition**
- **ACF and PACF Analysis**
- **Model Training with ARIMA and SARIMA**
- **Forecasting**
- **Performance Evaluation**

## 📊 Evaluation Metrics

| Metric | SARIMA | ARIMA |
|--------|--------|--------|
| RMSE   | 15.11  | 13.25  |
| MAE    | 13.84  | 11.98  |
| MAPE   | 8.56%  | 7.42%  |

## 📌 Insights
- **ARIMA model performed better** in predicting Apple stock prices.
- Lower RMSE, MAE, and MAPE values confirm ARIMA's accuracy.
- SARIMA may not add much value in the absence of strong seasonal patterns.

## 📎 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- statsmodels, pmdarima
