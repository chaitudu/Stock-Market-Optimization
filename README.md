# 📈 Stock Market Portfolio Optimization

## 📝 Introduction
Stock market portfolio optimization is the process of selecting the best combination of stocks to maximize returns while minimizing risk. This project implements **Modern Portfolio Theory (MPT)** to construct an efficient portfolio using **Python**.

We will use real-time and historical stock market data from **Yahoo Finance (yfinance API)** to analyze price trends, expected returns, volatilities, and correlations between different stocks. The goal is to identify an **optimal portfolio with the highest Sharpe ratio**.

---

## 🚀 Features
- Fetches real-time stock data using `yfinance`
- Computes expected returns and volatilities
- Calculates correlations between stocks
- Implements **Modern Portfolio Theory (MPT)**
- Finds the **efficient frontier** for optimal risk-return tradeoff
- Identifies the **maximum Sharpe ratio portfolio**

---

## 📦 Installation
Make sure you have Python installed (>=3.7). Then, install the required dependencies:

pip install yfinance numpy pandas matplotlib scipy
pip install yfinance
📈 How It Works
Step 1: Collects real-time/historical stock market data using yfinance
Step 2: Computes expected returns, volatilities, and correlations
Step 3: Uses Monte Carlo simulations to generate portfolio combinations
Step 4: Plots the efficient frontier to find the best risk-return balance
Step 5: Identifies the tangency portfolio with the maximum Sharpe ratio
The script will generate a scatter plot of possible portfolios along the efficient frontier and highlight the optimal portfolio

Optimal Portfolio Allocation:
AAPL: 40%
GOOGL: 30%
MSFT: 30%
Expected Return: 12.5%
Risk (Volatility): 8.2%
Sharpe Ratio: 1.52


🛠 Technologies Used
Python
yfinance (Stock Market Data)
NumPy & Pandas (Data Analysis)
Matplotlib (Data Visualization)
SciPy (Optimization)
