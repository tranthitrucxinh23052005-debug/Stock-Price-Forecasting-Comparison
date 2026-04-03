# 📈 Stock Price Forecasting Engine

## Overview
This repository presents a comparative study of machine learning and deep learning models for forecasting S&P 500 stock prices. The project focuses on optimizing forecasting accuracy for financial time-series data by evaluating traditional statistical methods against modern neural networks.

## Key Highlights
* **Model Comparison:** Built and evaluated ARIMA, Random Forest, and Long Short-Term Memory (LSTM) networks.
* **Performance Optimization:** Successfully reduced the Mean Absolute Percentage Error (MAPE) by **~25–30%** compared to the baseline ARIMA model.
* **Data Pipeline:** Implemented robust time-series preprocessing, including stationarity checks, scaling, and feature engineering (lagged variables, rolling statistics).

## Tech Stack
* **Language:** Python
* **Modeling:** Scikit-learn, TensorFlow/Keras (LSTM), Statsmodels (ARIMA)
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## Results
*(Insert an image here showing the predicted vs. actual stock prices curve)*
> The LSTM model demonstrated superior ability in capturing non-linear patterns and volatility clustering in the S&P 500 dataset, yielding the lowest MAPE among the tested models.

## Usage
1. Clone the repository: `git clone https://github.com/tranthitrucxinh23052005-debug/Stock-Price-Forecasting-Comparison-.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook `forecasting_engine.ipynb` to view the end-to-end pipeline.
