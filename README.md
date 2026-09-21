# Financial Market Analytics with Python

A Python-based financial analytics project exploring **10 years of market data** across six major stocks.

The goal is to go beyond simple stock-price comparisons and analyze **returns, volatility, downside risk, market relationships, and event-driven behavior**.

## Assets Analyzed

- Apple (AAPL)
- JPMorgan Chase (JPM)
- ExxonMobil (XOM)
- AMD (AMD)
- Coca-Cola (KO)
- Tesla (TSLA)

**Benchmark:** S&P 500 (SPY)  
**Market volatility indicator:** VIX  
**Period:** 2015–2024

## Analysis

The project includes:

- Daily return analysis
- Descriptive statistics
- Annualized volatility
- Skewness & kurtosis
- Normality testing
- Rolling volatility
- Maximum drawdown analysis
- Value at Risk (VaR)
- Conditional Value at Risk (CVaR)
- Return & squared-return autocorrelation
- Volatility clustering
- Beta estimation
- Correlation with the S&P 500
- Rolling market correlations
- Trading-volume analysis
- Earnings-day impact
- VIX vs. realized volatility
- Cumulative growth of $1

## Tech Stack

Python • Pandas • NumPy • SciPy • Statsmodels • Matplotlib • Seaborn • yfinance

## Key Idea

High returns don't tell the whole story.

By combining performance metrics with drawdowns, volatility, tail-risk measures, and market correlations, this project explores the **risk-return tradeoff** behind each stock's historical performance.

## Run the Project

Install the required libraries:

pip install yfinance pandas numpy scipy statsmodels matplotlib seaborn

Then run the Python script to download the market data, perform the analysis, and generate the visualizations.

## Customize It

The project is designed to be reusable. Simply replace the ticker symbols to analyze a different set of companies or build your own market comparison.
