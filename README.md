# Trader-Performance-vs-Market-Sentiment
# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior on Hyperliquid. The objective is to identify how market sentiment influences trader profitability, trading activity, and behavior, and to propose actionable trading strategies.

---

## Objective

- Analyze trader performance under different market sentiment conditions.
- Compare trading behavior during Fear and Greed periods.
- Identify trader segments based on performance.
- Generate actionable insights for better trading decisions.

---

## Dataset

### 1. Bitcoin Fear & Greed Index
- Date
- Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)

### 2. Hyperliquid Historical Trader Data
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Direction
- Closed PnL
- Fee
- Timestamp
- Other trading-related attributes

---

## Tools & Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

---

## Project Workflow

### Data Preparation
- Loaded both datasets
- Checked dataset dimensions
- Verified missing values
- Removed duplicates
- Converted timestamps to datetime
- Merged datasets using daily dates

### Feature Engineering
- Daily PnL
- Win/Loss Indicator
- Win Rate
- Average Trade Size
- Trades Per Day
- Long/Short Ratio
- Trader Segmentation

---

## Analysis Performed

- Profitability by Market Sentiment
- Win Rate by Market Sentiment
- Trade Frequency Analysis
- Average Trade Size Analysis
- Trader Segmentation

---

## Key Insights

- Trader profitability varies across different market sentiment conditions.
- Trading activity changes during Fear and Greed periods.
- Trader performance is distributed across Top, Average, and Low performers, indicating differences in trading consistency.

---

## Strategy Recommendations

### Recommendation 1
Reduce position size and follow stricter risk management during Fear periods because market uncertainty is generally higher.

### Recommendation 2
Avoid overtrading during Greed periods. Maintain disciplined position sizing and profit-taking strategies.

---

## Repository Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── Trader_Performance_Market_Sentiment_Analysis.ipynb
├── README.md
├── fear_greed_index.csv
├── historical_data.csv
└── output_charts/
```

---

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if needed.
3. Place both CSV files in the project directory.
4. Run all notebook cells in sequence.

---

## Author

**Suruchi Rawat**

Data Science & Analytics Intern Assignment

Submitted for **Primetrade.ai**
