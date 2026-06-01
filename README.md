# Bitcoin Sentiment vs Trader Performance Analysis

## Overview

This project explores the relationship between Bitcoin market sentiment and trader performance using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data.

The objective is to uncover patterns between market sentiment and trading outcomes, helping identify factors that influence profitability and trading behavior.

---

## Objective

Analyze how different market sentiment conditions affect:

- Trader profitability
- Trading activity
- Position sizing behavior
- Overall market performance

The analysis combines sentiment data with historical trade records to generate actionable insights for data-driven trading strategies.

---

## Datasets

### 1. Bitcoin Fear & Greed Index
Provides daily market sentiment classifications:

- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

### 2. Hyperliquid Historical Trader Data
Contains detailed trading information including:

- Account
- Symbol
- Execution Price
- Trade Size
- Side (Buy/Sell)
- Closed PnL
- Leverage
- Timestamp

---

## Methodology

### Data Preprocessing
- Cleaned and standardized datasets
- Converted timestamps to date format
- Handled missing values
- Prepared data for analysis

### Data Integration
- Merged trading data with sentiment data using trade dates

### Exploratory Data Analysis
- Average Closed PnL by Sentiment
- Total Profit by Sentiment
- Average Position Size by Sentiment
- Feature Importance Analysis

---

## Key Findings

### 1. Extreme Greed Generated Highest Average Profit

Trades executed during Extreme Greed conditions achieved the highest average Closed PnL, indicating strong profitability during bullish market phases.

### 2. Fear Produced Highest Total Profit

Although average profitability was highest during Extreme Greed, Fear periods generated the largest cumulative profits due to increased trading activity and larger position sizes.

### 3. Larger Positions Were Taken During Fear

Traders allocated more capital during Fear conditions, suggesting greater confidence in identifying opportunities during market downturns.

### 4. Position Size Is the Strongest Driver of Profitability

Feature importance analysis revealed:

| Feature | Relative Importance |
|----------|-------------------|
| Position Size | ~87% |
| Market Sentiment | ~10% |
| Trade Side | ~3% |

This highlights the critical role of risk and capital management in trading performance.

---

## Visualizations

The project includes the following visual analyses:

- Average Closed PnL by Sentiment
- Total Profit by Sentiment
- Average Position Size by Sentiment
- Feature Importance Analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```text
bitcoin-sentiment-trader-performance-analysis/
│
├── notebooks/
│   └── analysis.ipynb
│
├── visualizations/
│   ├── average_pnl_by_sentiment.png
│   ├── total_profit_by_sentiment.png
│   ├── average_position_size.png
│   └── feature_importance.png
│
├── reports/
│   └── Final_Report.pdf
│
└── README.md
```

---

## Conclusion

The analysis demonstrates a clear relationship between Bitcoin market sentiment and trader behavior. While Extreme Greed conditions generated the highest average returns, Fear periods contributed the highest overall profits. Position size emerged as the most influential factor affecting profitability, emphasizing the importance of effective capital allocation and risk management in trading strategies.

---


