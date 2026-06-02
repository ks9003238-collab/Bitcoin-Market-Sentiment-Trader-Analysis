# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data.

The objective is to identify how market sentiment influences trader profitability, trading behavior, position sizes, and overall performance. The analysis uncovers patterns that can help traders make more informed decisions and develop sentiment-driven trading strategies.

---

## Problem Statement

Cryptocurrency markets are heavily influenced by investor psychology. The Fear & Greed Index provides a measure of market sentiment, while trading records reveal actual trader behavior.

This project aims to answer:

* Are traders more profitable during Fear or Greed periods?
* How does market sentiment affect trading activity?
* Which sentiment conditions generate the highest profits or losses?
* Does trader behavior change significantly across different sentiment regimes?

---

## Datasets

### 1. Bitcoin Fear & Greed Index

Features:

* Date
* Sentiment Score (0–100)
* Classification

  * Extreme Fear
  * Fear
  * Greed
  * Extreme Greed

### 2. Hyperliquid Historical Trading Data

Features:

* Account
* Coin
* Execution Price
* Size Tokens
* Size USD
* Side (BUY/SELL)
* Timestamp
* Start Position
* Direction
* Closed PnL
* Transaction Details

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook
* Streamlit

---

## Project Workflow

### Data Collection

* Historical trader dataset
* Fear & Greed Index dataset

### Data Cleaning

* Missing value handling
* Duplicate removal
* Datetime conversion
* Feature standardization

### Data Integration

Merged trading records with sentiment data using trade dates.

### Feature Engineering

Created additional features:

* Win/Loss Indicator
* Profit Category
* Trade Hour
* Sentiment Labels

### Exploratory Data Analysis

Performed:

* Sentiment Distribution Analysis
* Profitability Analysis
* Win Rate Analysis
* Buy vs Sell Analysis
* Trade Size Analysis
* Coin Performance Analysis
* Top Trader Analysis

### Statistical Testing

Applied ANOVA to determine whether profitability differs significantly across sentiment categories.

---

## Key Analyses

### Profitability by Sentiment

Analyzed average, median, and total profit/loss across:

* Extreme Fear
* Fear
* Greed
* Extreme Greed

### Win Rate Analysis

Calculated winning trade percentages across sentiment conditions.

### Trading Behavior Analysis

Compared:

* Buy vs Sell frequency
* Trade volume
* Position sizes

### Coin Performance

Evaluated performance of different cryptocurrencies under varying market sentiments.

### Top Traders Analysis

Identified the most profitable trader accounts.

---

## Visualizations

The project includes:

* Average PnL by Sentiment
* Total PnL by Sentiment
* Win Rate by Sentiment
* Trade Count by Sentiment
* Buy vs Sell Distribution
* PnL Distribution Boxplots
* Trade Size Comparison
* Correlation Heatmap

---

## Results & Insights

Key findings include:

* Trader profitability varies across market sentiment conditions.
* Trading behavior changes significantly during Fear and Greed periods.
* Win rates differ among sentiment categories.
* Market sentiment can be used as a useful indicator for risk management and strategy development.

---

## Author

**Kishor Solanki**

Data Science Enthusiast | Python | Data Analytics

---

## License

This project is developed for educational and portfolio purposes.

