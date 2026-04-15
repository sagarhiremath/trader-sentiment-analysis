# Trader Performance vs Market Sentiment Analysis

## 📌 Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior and performance.

## 📊 Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid Historical Trader Data

## ⚙️ Methodology
- Cleaned and validated datasets (no missing values or duplicates)
- Converted timestamps and aligned both datasets on daily level
- Merged sentiment data with trader data
- Created key metrics:
  - Daily PnL
  - Win rate
  - Trade frequency
  - Average trade size

## 📈 Key Insights
- Highest profitability observed during Extreme Greed conditions
- Traders take larger positions during Fear periods
- Trading activity and win rates increase during Greed phases

## 💡 Strategy Recommendations
- Reduce trade size during Fear conditions due to lower win rates
- Increase participation during Greed phases with controlled risk

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib

## ▶️ How to Run
1. Open the notebook `trader-sentiment-analysis (Primetrade.ai).ipynb`
2. Run all cells sequentially
