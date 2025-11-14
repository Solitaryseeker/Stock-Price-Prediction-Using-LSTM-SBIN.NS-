#  SBIN Stock Price Prediction Using LSTM

This project predicts the future stock prices of SBI (SBIN.NS) using a Long Short-Term Memory (LSTM) neural network.
The model is trained on historical Close prices sourced from Yahoo Finance and provides both evaluation on test data and future forecasting.

*The workflow includes:*
* Data collection using Yahoo Finance
* Data cleaning & preprocessing
* Visual exploration
* LSTM model building
* Training, evaluation, and prediction
* Visual comparison between predicted vs. actual data

# Data Collection
The dataset is downloaded using the yfinance library:

* Ticker: SBIN.NS
* Date Range: 2000-01-01 to present
* Stock downloaded using: [Yahoo Finance](https://finance.yahoo.com/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAADfGs_8epfXwZqTbpwgQrSHrsN7kvEnmUrku7DAVrAohvYy2z4jQTjeLQHWkvxkBMSq9kKkgAbaYGhf3JnK11_VOTROIvBpyLbZRJ3_KxPLQ0WkRcR0yaPGuZStsUUHNm9jXgRGIQJhddApMoI2IQ5i1Cc3cJtqxP2WaJcn9sxYQ)
* Features available
The data is stored into a CSV file for further processing.
Dataset is also saved as a CSV for reuse.
