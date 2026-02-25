# 📈 Quantitative Portfolio Tracker

A robust Python-based financial tool designed to track a live basket of equities, calculate key performance metrics, and visualize asset allocation. Built for active traders and investors, this script fetches real-time market data to provide an immediate snapshot of portfolio health during and after trading hours.

## ✨ Features

* **Real-Time Data Extraction:** Integrates with the `yfinance` API to pull live and historical stock data directly from the National Stock Exchange (NSE).
* **Advanced Financial Metrics:** Automatically calculates absolute returns, Compound Annual Growth Rate (CAGR), and the Sharpe Ratio to evaluate risk-adjusted performance.
* **Dynamic Visualization:** Generates dark-themed, publication-ready charts using `matplotlib` to display the portfolio's equity curve and precise asset allocation percentages.
* **Scalable Architecture:** Easily expandable to accommodate hundreds of tickers and different asset classes.

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **Core Libraries:** * `pandas` & `numpy`: For high-performance vectorized data manipulation and financial calculations.
  * `yfinance`: For reliable market data ingestion.
  * `matplotlib`: For rendering analytical dashboards.

## 🚀 Getting Started

### Prerequisites
Ensure Python is installed on your machine. Install the required dependencies using pip:
```bash
pip install yfinance pandas matplotlib numpy
