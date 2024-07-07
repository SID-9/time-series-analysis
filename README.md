# ARIMA Model for Stock Market Prediction

## Project Overview

This project involves building an ARIMA (AutoRegressive Integrated Moving Average) model to predict stock prices using historical data. The dataset used for this project is the HCLTECH.csv file from Kaggle, which contains stock market data for HCL Technologies. The model aims to forecast future stock prices based on past performance, leveraging time series analysis techniques.

## Repository Structure

- **arima-model-18-8-23.ipynb**: The Jupyter Notebook containing the complete implementation of the ARIMA model for stock market prediction.

## Motivation

Stock market prediction is a challenging task due to the inherent volatility and complexity of financial markets. Accurate predictions can provide valuable insights for investors, helping them make informed decisions. This project demonstrates the application of the ARIMA model, a popular and effective method for time series forecasting, to predict stock prices.

## Dataset

The dataset used is sourced from Kaggle and contains historical stock prices for HCL Technologies. It includes columns such as date, open price, high price, low price, close price, and volume. The data is processed to focus on the closing prices, which are used for model training and prediction.

## Preprocessing Techniques

1. **Data Cleaning**: Handling missing values, if any, and ensuring data consistency.
2. **Exploratory Data Analysis (EDA)**: Visualizing stock price trends and patterns over time.
3. **Stationarity Check**: Testing for stationarity using the Augmented Dickey-Fuller (ADF) test.
4. **Differencing**: Applying differencing to make the time series stationary, if required.

## Model Implementation

The ARIMA model is implemented using the following steps:

1. **Parameter Selection**: Determining the optimal values for p (autoregressive order), d (differencing order), and q (moving average order) using ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) plots.
2. **Model Fitting**: Fitting the ARIMA model to the historical stock price data.
3. **Forecasting**: Using the fitted model to predict future stock prices and evaluating the model's performance.

## Results

The ARIMA model provides accurate forecasts of future stock prices based on historical data. The notebook includes visualizations of the predicted vs. actual stock prices, along with performance metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Future Work

- **Model Optimization**: Experiment with seasonal ARIMA (SARIMA) and other time series models to improve forecasting accuracy.
- **Additional Features**: Incorporate other relevant features such as trading volume, market indices, and macroeconomic indicators.
- **Real-time Predictions**: Develop an API for real-time stock price predictions using the trained model.

## Conclusion

This project illustrates the application of the ARIMA model for stock market prediction, demonstrating its effectiveness in forecasting future stock prices based on historical data. By leveraging time series analysis techniques, the model provides valuable insights for investors and contributes to more informed decision-making in the stock market.

## Author

**Siddharth Upadhyay**  
