# Risk-Adjusted Asset Performance Benchmarking Against the S&P 500

## Overview

This project evaluates the performance of multiple financial assets using risk-adjusted metrics and benchmark comparison techniques. The analysis focuses on annualized returns, volatility, Sharpe ratios, and compounded returns to assess whether individual assets outperformed the broader market (S&P 500) on both a raw and risk-adjusted basis.

---

## Assets Used

* Apple (AAPL)
* JPMorgan Chase (JPM)
* Coca-Cola (KO)
* Exxon Mobil (XOM)
* S&P 500 (^GSPC)

---

## Objectives

* Analyze asset performance over time
* Measure annualized returns
* Measure annualized volatility
* Calculate Sharpe ratios
* Compare assets against the S&P 500 benchmark
* Evaluate compounded portfolio growth
* Identify risk-adjusted outperformers

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* yfinance

---

## Concepts Applied

* Daily Returns
* Annualized Returns
* Annualized Volatility
* Sharpe Ratio
* Compounded Returns
* Benchmark Comparison
* Risk-Adjusted Performance
* Cumulative Growth of $1 Invested

---

## Methodology

1. Collect historical asset data using yfinance
2. Clean and preprocess adjusted closing prices
3. Calculate daily returns
4. Annualize returns and volatility
5. Compute Sharpe ratios for each asset
6. Calculate compounded cumulative returns
7. Benchmark all assets against the S&P 500 Index
8. Visualize and interpret comparative performance

---

## Visualizations

* Cumulative Returns Chart
* Annualized Return Comparison
* Volatility Comparison
* Sharpe Ratio Comparison

---

## Key Insights

* Exxon Mobil (XOM) produced the strongest overall returns, with the stock price increasing by more than 2x over the analyzed period.

* Exxon Mobil (XOM) also achieved the highest Sharpe Ratio, indicating the strongest risk-adjusted performance among the selected assets.

* Apple (AAPL) was the most volatile asset, indicating greater price fluctuations and higher investment risk.

* Coca-Cola (KO) was the only asset to underperform the S&P 500 benchmark in terms of overall returns.

* The S&P 500 achieved stronger risk-adjusted returns than both JPMorgan Chase (JPM) and Coca-Cola (KO).

---

## Data Source

Historical market data retrieved using Yahoo Finance through the yfinance API.
