# Portfolio-Optimization-using-Python

## Overview
This project applies **Modern Portfolio Theory** to construct efficient portfolios from historical asset returns. It compares equal-weight, risk-parity, and maximum-Sharpe allocations under realistic constraints.

## Objectives
- Fetch and preprocess multi-asset historical prices using Python.
- Build the efficient frontier using Monte Carlo simulation and optimization.
- Evaluate allocations via Sharpe ratio, drawdowns, VaR, and CVaR.

## Data Sources
- Yahoo Finance (`yfinance`) for historical prices  
- S&P 500 ETF (SPY) as benchmark  
- 3M T-Bill yield (FRED) as risk-free rate

## Methods & Tools
- **Python Libraries:** pandas, NumPy, matplotlib, SciPy, statsmodels, seaborn
- **Techniques:** Mean-Variance Optimization, Risk Parity, VaR/CVaR

## Results
- Max-Sharpe portfolio outperformed equal-weight by **X% annualized return** with lower volatility.
- Risk-parity portfolio reduced drawdowns by **Y%** vs equal-weight.


## References
- Markowitz (1952) Portfolio Selection.

