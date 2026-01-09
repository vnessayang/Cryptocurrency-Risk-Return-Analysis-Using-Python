# Cryptocurrency-Risk-Return-Analysis-Using-Python
This project analyzes the risk and return characteristics of major cryptocurrencies using historical market data.
The analysis focuses on Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC), and XRP over a 5-year period, applying statistical and financial risk measures commonly used in quantitative finance.

🚀 Project Overview

The notebook explores:

Historical price behavior of major cryptocurrencies

Log return distributions and volatility

Downside risk probabilities

Value at Risk (VaR)

Correlation and covariance between crypto assets

Linear regression to understand BTC return drivers

This project is suitable for:

Financial risk analysis portfolios

Quantitative finance / fintech learning

Crypto market research

GitHub showcase for finance, data, or risk roles

📁 Data Source

Yahoo Finance via yfinance

Tickers used:

BTC-USD

ETH-USD

LTC-USD

XRP-USD

Frequency: Daily

Time horizon: Last 5 years (rolling from execution date)

Downloaded data is stored locally in the data/ folder as CSV files.

🔧 Tools & Libraries

Python 3

numpy – numerical computation

pandas – data manipulation

matplotlib & seaborn – visualization

yfinance – market data retrieval

scipy.stats – probability & distribution analysis

statsmodels – regression analysis

📈 Analysis Breakdown
1. Price & Descriptive Statistics

Summary statistics (mean, std, quartiles)

Price trend visualization for all assets

2. Log Daily Returns

Computation of log returns

Distribution analysis via histograms

Volatility behavior visualization

3. Risk Probability Estimation

Probability of BTC daily loss greater than 5%

Probability of 100% drawdown over 220 trading days

Probability of 100% upside over 220 trading days
(assuming normal return distribution)

4. Value at Risk (VaR)

VaR at 95% confidence level

VaR at 50% confidence level

Quantile-based downside risk measurement

5. Covariance & Correlation

Covariance matrix of crypto returns

Correlation heatmap

Pairwise scatter plots for dependency analysis

6. Regression Analysis

BTC log return as dependent variable

ETH, LTC, and XRP returns as explanatory variables

OLS regression using statsmodels

📊 Sample Outputs

Price trend charts

Log return histograms

Correlation heatmap

Regression summary statistics

(See the notebook for full visualizations and outputs.)
