# RSI-Stock-Analysis

This project downloads historical stock price data using yfinance, calculates the Relative Strength Index (RSI) indicator and visualizes both the stock price and RSI to help identify potential overbought or oversold conditions.

Features:
- Fetches stock data from Yahoo Finance
- Calculates RSI with a customizable window size
- Plots closing price and RSI with visual markers for overbought (70) and oversold (30) levels
- Clean and readable output table with recent RSI values

Requirements:
- Python 3.7+
- pandas
- numpy
- matplotlib
- yfinance
- tabulate (for pretty table output)

Installation:
pip install pandas numpy matplotlib yfinance tabulate

Usage:
- Run the script to fetch Apple stock data for the past 6 months, calculate RSI, print the latest values, and display the charts:

python rsi_analysis.py
To analyze a different stock, change the ticker symbol in the script:

df = yf.download('MSFT', period='6mo', interval='1d')  # Microsoft example

License:
- This project is licensed under the MIT License.

