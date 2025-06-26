# trading-sentiment-analysis
Analyzing Bitcoin trader performance under Fear &amp; Greed market sentiment using Hyperliquid historical data.
# Trading Sentiment Analysis

## Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance metrics from Hyperliquid historical trade data. The goal is to identify patterns in trading performance under different market sentiment conditions and derive actionable insights for trading strategies.

## Key Objectives
1. Explore how market sentiment affects trading profitability
2. Identify optimal trading conditions based on sentiment
3. Analyze risk-return profiles across sentiment categories
4. Provide data-driven recommendations for sentiment-aware trading strategies

## Dataset Descriptions

### 1. Historical Trader Data (Hyperliquid)
- **Source**: Provided CSV file
- **Key Columns**:
  - `Timestamp IST`: Trade execution time
  - `Coin`: Cryptocurrency symbol (BTC in this analysis)
  - `Side`: Trade direction (BUY/SELL)
  - `Closed PnL`: Profit/loss in USD
  - `Size USD`: Trade size in USD
  - Other metadata about trades

### 2. Fear & Greed Index Data
- **Source**: Alternative.me Crypto Fear & Greed Index
- **Key Columns**:
  - `date`: Observation date
  - `value`: Numerical sentiment score (0-100)
  - `value_classification`: Text classification (Extreme Fear to Extreme Greed)

## How to Run the Analysis

### Prerequisites
- Python 3.8+
- Required libraries (install via `pip install -r requirements.txt`)

### Execution Steps
1. Place the dataset files in the project directory:
   - `historical_data.csv`
   - `fear_greed_index.csv`

2. Run the analysis:
   ```bash
   python trading_sentiment_analysis.py
