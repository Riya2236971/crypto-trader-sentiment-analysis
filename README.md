# Crypto Trader Sentiment Analysis

## Objective
Analyze how Bitcoin market sentiment (Fear & Greed) impacts trader performance and behavior using historical trade data.

## Datasets
- Bitcoin Market Sentiment (Fear & Greed Index)
- Historical Trader Data (Hyperliquid)

## Methodology
- Data cleaning and validation
- Date-level alignment of sentiment and trades
- Feature engineering (PnL, win rate, position size, frequency, consistency)
- Segmentation and comparative analysis

## Analysis Questions Answered
- Performance differences between Fear vs Greed days
- Behavioral changes based on sentiment
- Trader segmentation:
  - Frequent vs Infrequent
  - High-risk vs Low-risk
  - Consistent vs Inconsistent

## Key Insights
- Traders increase risk during Fear and Extreme Greed
- Frequent traders perform better in Greed periods
- Consistent traders show stable performance across sentiments

## Actionable Recommendations
- Reduce position sizes during Fear and Extreme Greed
- Enforce stricter limits for high-risk traders
- Encourage disciplined trading during volatile sentiment phases

## How to Run
1. Open `primeTrade_analysis.ipynb`
2. Run all cells top to bottom
3. Ensure required libraries: pandas, numpy, matplotlib, seaborn
