# Gold Price Behavior During Financial Crises

![screenshot-localhost_8888-2025 03 31-11_49_10](https://github.com/user-attachments/assets/aac1ff8f-45a1-40f7-9731-80f424285a13)

### Overview

This project analyzes the behavior of gold prices during major financial crises to assess its role as a safe-haven asset. Using historical price data from 1993 to 2022, I examined gold’s performance across different timeframes (daily, monthly, and quarterly) and evaluated key financial metrics such as returns, volatility, and drawdowns. Additionally, I built LSTM (Long Short-Term Memory) and XGBoost models to forecast gold prices and compare their predictive performance.

### Key Objectives

- Investigate gold price trends during financial crises.
- Evaluate gold’s performance as a safe-haven asset based on returns, volatility, and drawdowns.
- Compare normal vs. crisis volatility and assess risk.
- Build machine learning models (LSTM & XGBoost) to forecast gold prices.

### Dataset

The dataset includes historical gold price data (in USD) along with other currency values, covering various financial crises:

- Asian Financial Crisis (1997-1998)
- Dot-com Bubble (2000-2002)
- Global Financial Crisis (2007-2009)
- European Debt Crisis (2010-2012)
- COVID-19 Pandemic (2020)
- 2022 Inflation Crisis

### Project Workflow

1. Preprocessing Data
2. Safe Haven Analysis
3. Train and Evaluate Models
4. Visualization

### Key Findings

- Gold had positive returns in 4 out of 6 crises (67%), reinforcing its reputation as a hedge.
- Volatility increased in 4 out of 6 crises, indicating higher price fluctuations during economic instability.
- LSTM outperformed XGBoost, achieving a lower RMSE (23.17 vs. 27.80), suggesting deep learning is more effective for gold price forecasting.

### Future Work

1. Incorporate macroeconomic indicators (inflation, interest rates, stock market trends).
2. Use sentiment analysis on news data to predict gold price movements.
3. Experiment with other deep learning architectures (GRU, Transformer models) for improved forecasting.

### Source

![Gold Price 1979 to Present from Kaggle](https://www.kaggle.com/datasets/jishnukoliyadan/gold-price-1979-present)
