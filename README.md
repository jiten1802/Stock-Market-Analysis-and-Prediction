# Stock Market Analysis and Prediction
This project analyzes and predicts stock prices of Apple, Google, Microsoft, and Amazon using historical data and LSTM models.

## Overview
Data Collection: Historical stock data for AAPL, GOOG, MSFT, and AMZN is gathered using yfinance.
EDA: Visualize trends with Adjusted Close Prices, Moving Averages, Daily Returns, and Correlation Analysis.
LSTM Model: An LSTM neural network is trained on Apple's stock data to predict future prices.

## Key Steps
Data Preprocessing: Scale data and create training/testing datasets using a sliding window approach.
Model Training: Train an LSTM model with two layers on Apple's stock data.
Prediction: Predict future prices and evaluate performance using RMSE.

## Results
Predicted vs. actual prices are plotted for comparison.
