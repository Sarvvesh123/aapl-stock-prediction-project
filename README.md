# AAPL Stock Movement Prediction

This project builds a Random Forest classifier in Python to predict daily AAPL stock price movement using historical price data from 1990 through March 2025. The model achieves a precision score of approximately 0.52 on the test set.

## Project Overview

- Utilizes historical stock data (Open, Close, High, Low, Volume) sourced via `yfinance`.
- Implements a Random Forest classifier with backtesting to evaluate predictive performance.
- Targets binary classification: whether the stock price will increase the following day.
- Achieved a precision of 0.52 on held-out data.

### Setup

In Google Colab, install the `yfinance` package by running:
import yfinance as yf

```bash
!pip install yfinance
