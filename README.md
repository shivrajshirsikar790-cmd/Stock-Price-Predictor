# Stock Price Predictor

A machine learning project that predicts stock prices using Linear Regression.

## Overview
This project uses historical stock data to train a Linear Regression model and predict future stock prices. The model achieves **99.44% accuracy** (R2 Score) on the test data.

## Features
- Fetches real-time stock data using yfinance API
- Uses Linear Regression for price prediction
- Visualizes actual vs predicted prices
- Calculates performance metrics (MSE, MAE, R2 Score)

## Technologies Used
- Python
- NumPy & Pandas
- Scikit-learn
- Matplotlib
- yfinance

## Dataset
- Stock: RELIANCE.NS (Reliance Industries)
- Date Range: 2020-01-01 to 2024-11-27
- Features: Open, High, Low, Volume
- Target: Close Price

## Results
- R2 Score: 99.44%
- Model successfully predicts stock closing prices

## How to Run
1. Open the notebook in Google Colab
2. Run all cells sequentially
3. View the predictions and visualizations

## Author
Created for Codec Technologies Internship

## Colab Notebook
[Open in Google Colab](https://colab.research.google.com/drive/1oCASwPKMr_YG-BU7VLKg38qFLw8rDPv6)
