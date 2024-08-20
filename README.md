# Stock Market Analysis and Prediction
This project analyzes and predicts stock prices of Apple, Google, Microsoft, and Amazon using historical data and LSTM models.

## Overview
**1. **Data Collection:**** Historical stock data for AAPL, GOOG, MSFT, and AMZN is gathered using yfinance.
**2. **EDA:**** Visualize trends with Adjusted Close Prices, Moving Averages, Daily Returns, and Correlation Analysis.
**3. LSTM Model:** An LSTM neural network is trained on Apple's stock data to predict future prices.

## Key Steps
**1. Data Preprocessing:** Scale data and create training/testing datasets using a sliding window approach.
**2. Model Training:** Train an LSTM model with two layers on Apple's stock data.
**3. Prediction:** Predict future prices and evaluate performance using RMSE.

## Results
Predicted vs. actual prices are plotted for comparison.
