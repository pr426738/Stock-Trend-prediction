1. Libraries Used:

numpy, pandas for data manipulation.
yfinance for fetching stock data.
keras to load the pre-trained LSTM model.
matplotlib for plotting.
streamlit for creating the web app interface.
2.Workflow:

Takes a stock symbol input (default is GOOG).
Downloads historical stock data from Yahoo Finance.
Displays stock prices with moving averages (MA50, MA100, MA200).
Prepares the data, scales it, and predicts future prices using the LSTM model.
Plots both the original and predicted prices for comparison.
