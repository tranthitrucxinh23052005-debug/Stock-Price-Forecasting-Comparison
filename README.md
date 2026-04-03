# 📈 Stock Price Forecasting: ARIMA vs. Random Forest vs. LSTM

## 📌 Project Overview
This project performs a comparative analysis of three different approaches to time-series forecasting using the S&P 500 stocks dataset. The goal is to evaluate the performance of traditional statistical models, ensemble learning, and deep learning in predicting stock prices.

## 🤖 Models Implemented
1. **ARIMA (AutoRegressive Integrated Moving Average):** A classical statistical approach for stationary time-series data.
2. **Random Forest Regressor:** An ensemble machine learning method used to capture non-linear relationships.
3. **LSTM (Long Short-Term Memory):** A Recurrent Neural Network (RNN) architecture specialized in learning long-term dependencies in sequential data.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** TensorFlow/Keras (LSTM), Scikit-learn (Random Forest), Statsmodels (ARIMA), Pandas, NumPy.
* **Data Source:** S&P 500 Stocks dataset via KaggleHub.

## 📊 Evaluation Metrics
To ensure a fair comparison, all models are evaluated using:
* **RMSE** (Root Mean Squared Error)
* **MAE** (Mean Absolute Error)
* **MAPE** (Mean Absolute Percentage Error)

## 📈 Key Findings
* **LSTM** showed superior performance in capturing complex patterns but required more computational resources.
* **ARIMA** performed well on stable, linear trends but struggled with high volatility.
* **Random Forest** provided a solid baseline with fast training times.

---
**Author:** Tran Thi Truc Xinh (TS)
