# Portfolio Risk Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)

A Python-based project simulating how market risk teams measure and monitor portfolio risk using real financial data.

This project analyzes the risk of an equity portfolio by evaluating return, volatility, and downside risk using Value at Risk (VaR).

---

## Key Features
- Calculated daily returns and annualized volatility for multiple assets
- Built an equal-weighted portfolio to analyze aggregated risk exposure
- Computed 95% and 99% Value at Risk (VaR) to estimate potential losses under adverse market conditions
- Performed stress analysis based on historical return distributions
- Visualized asset performance and portfolio risk distribution

---

## Tools Used
- Python (pandas, numpy, matplotlib)
- yfinance (data source)

---

## Key Insights
- NVDA exhibited significantly higher return (~65%) and volatility (~55%), acting as the primary risk driver in the portfolio  
- Despite equal weighting, asset-level risk contributions were uneven due to differing volatility levels  
- The portfolio’s 95% VaR (~ -3%) indicates potential daily losses under normal market conditions  
- Diversification across assets helps reduce overall portfolio risk compared to single-stock exposure  

---

## Author
Tiffany Tong
