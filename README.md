# Trader Behavior vs Market Sentiment Analysis
Analysis of trader behavior under different Bitcoin market sentiment regimes

## Objective
Analyze how Bitcoin market sentiment (Fear & Greed Index) influences trader behavior and performance using historical Hyperliquid trading data.

## Dataset
- Bitcoin Fear & Greed Index (daily sentiment)
- Hyperliquid Historical Trader Data

## Key Highlights
- Cleaned and merged trader-level data with daily sentiment data
- Performed EDA to study PnL distributions and trading activity across sentiment regimes
- Observed higher volatility during Extreme Fear and Extreme Greed periods
- Found weak linear correlation between sentiment and PnL, indicating sentiment impacts risk behavior more than direct profitability
- Demonstrated a simple sentiment-aware mock strategy that reduces exposure during Extreme Greed

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Google Colab

## Conclusion
Market sentiment acts as a contextual risk management signal rather than a standalone profit predictor.  
Incorporating sentiment-aware risk controls can support more disciplined trading decisions.
