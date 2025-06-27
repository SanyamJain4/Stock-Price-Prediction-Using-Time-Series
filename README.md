📈 Stock Price Prediction Using Time Series

This repository presents time series forecasting models applied to stock market data, using both statistical and deep learning methods to predict future stock prices.

---

## 🚀 Models Implemented

### 📘 Notebook 1: ARIMA-Based Forecasting
- Implements classical **ARIMA** model for univariate stock price prediction
- Covers data preprocessing, model fitting, and residual analysis

### 📙 Notebook 2: Hybrid ARIMA + LSTM Model
- Extends the previous work by combining **ARIMA** (for linear trends) and **LSTM** (for nonlinear patterns)
- Hybrid pipeline integrates statistical and neural approaches for improved accuracy

---

## 📁 Repository Structure

```
📦 Stock-Price-Prediction-Using-Time-Series
├── 📓 ARIMA_Model.ipynb                  # Implements ARIMA model
├── 📓 ARIMA_LSTM_Hybrid_Model.ipynb      # Combines ARIMA with LSTM                 
├── 📄 README.md                          # Project overview
```

---

## 🧠 Features

- Exploratory analysis and visualization
- Differencing and stationarity checks
- ARIMA parameter tuning via AIC
- LSTM model built on ARIMA residuals
- Forecasting and performance comparison

---

## 📊 Evaluation Metrics

- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)
- R² Score
- Actual vs Predicted plots
