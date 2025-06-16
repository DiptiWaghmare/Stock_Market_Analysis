# 📈 Stock Market Analysis

This project explores and analyzes stock market trends using historical data from **Yahoo Finance**. It includes visualizations, key metrics, and insights to help understand stock behavior over time for selected companies.

## 📌 Overview

The aim of this project is to:

* Analyze historical stock data for selected companies
* Perform time series visualizations of Open, Close, High, Low prices
* Compare stock performance across different companies
* Draw insights about trends, volatility, and correlations

## 📊 Tools & Technologies

* **Python**
* **Pandas** for data manipulation
* **NumPy** for numerical computations
* **Matplotlib** and **Seaborn** for data visualization
* **yfinance** for fetching historical stock data
* **Jupyter Notebook** for analysis

## 🔍 Features

* Fetches real-time data using `yfinance`
* Displays key statistics: Open, Close, High, Low, Volume
* Time-series line plots for visualizing price movement
* Comparative analysis between different companies
* Moving Average calculation and visualization


## 📌 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/DiptiWaghmare/Stock_Market_Analysis.git
   cd Stock_Market_Analysis
   ```
2. Install dependencies:

   ```bash
   pip install yfinance pandas matplotlib seaborn
   ```
3. Run the notebook:

   ```bash
   jupyter notebook
   ```
   

## 💡 Insights

* Stocks tend to show strong trends over longer durations.
* Moving averages help identify entry/exit points.
* Volume spikes often signal volatility or trend shifts.

## 🧠 Future Scope

* Add forecasting models (ARIMA, Prophet, LSTM)
* Integrate technical indicators (MACD, RSI, Bollinger Bands)
* Build a Streamlit or Dash app for interactive dashboards
