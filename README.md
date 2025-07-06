# Bitcoin Price Prediction Using Machine Learning & Deep Learning

## Overview

This project focuses on short-term Bitcoin price prediction using high-frequency (1-minute) OHLC and volume data. It explores both traditional time-series models and deep learning architectures to forecast Bitcoin's closing price, addressing challenges such as volatility, non-stationarity, and data gaps.

## Features

- Exploratory Data Analysis (EDA)
- Time Series Decomposition & Transformation
- Autocorrelation Analysis (ACF/PACF)
- Statistical Modeling (ARIMA, SARIMA, SARIMAX)
- Deep Learning Models (RNN, LSTM, GRU, Multi-feature GRU)
- Hyperparameter Tuning & Regularization
- Performance Evaluation (RMSE, MAE, R², MAPE)

## Dataset

- **Source:** 1-minute Bitcoin OHLC and volume data from multiple exchanges
- **Attributes:** Timestamp, Open, High, Low, Close, Volume
- **Notes:** Data includes missing values and is resampled for efficiency

## Approach

1. **Data Cleaning & Preprocessing:**  
   Handle missing values, resample data, and create new features (e.g., moving averages).
2. **Exploratory Analysis:**  
   Visualize trends, check for stationarity, and decompose the series.
3. **Modeling:**  
   - Fit and evaluate ARIMA, SARIMA, and SARIMAX models.
   - Build and train deep learning models (RNN, LSTM, GRU) using past price sequences and engineered features.
   - Tune hyperparameters and apply regularization techniques.
4. **Evaluation:**  
   Assess models using RMSE, MAE, R², and MAPE.

## Usage

1. **Clone the Repository**
2. **Install Dependencies**
3. **Prepare the Dataset**
4. **Run the Notebooks/Scripts**
5. **Review Results and Visualizations**

## Results

- Deep learning models, especially multi-feature GRUs, significantly outperform traditional statistical models.
- Incorporating additional features (e.g., Open price, moving averages) enhances predictive accuracy.
- Proper hyperparameter tuning and regularization are essential for robust performance.

## Future Work

- Integrate additional exogenous features (e.g., sentiment indicators, macroeconomic data)
- Explore advanced volatility models (e.g., GARCH)
- Deploy models for real-time prediction and trading strategies

