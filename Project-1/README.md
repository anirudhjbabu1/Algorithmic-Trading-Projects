# Statistical Arbitrage: Pairs Trading

Instead of predicting one stock, you predict the relationship between two.

The Goal: Find two stocks that are historically correlated (e.g., ICICI Bank and HDFC Bank). When the spread between them widens significantly, you short the "expensive" one and buy the "cheap" one, betting they will converge.

Key Skills: Cointegration (Augmented Dickey-Fuller test), Z-score calculation, and Mean Reversion.

Dataset: Daily or hourly data from yfinance or NSE historical archives.

Implementation: Use Python (Statsmodels, Pandas).
