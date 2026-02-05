# Trader Performance vs Market Sentiment

## Overview
This project analyzes how market sentiment (Fear and Greed) affects trader behavior and performance in the cryptocurrency market. The study uses historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

## Data Used
- Bitcoin Fear & Greed Index (daily sentiment classification)
- Hyperliquid historical trader data

## Methodology
- Cleaned and aligned both datasets at a daily level
- Merged trader data with market sentiment
- Calculated metrics such as daily PnL, win rate, trade count, and long/short ratio
- Compared trader behavior during Fear and Greed periods

## Key Observations
- Trading activity increases during Greed periods
- Fear periods show higher volatility in daily PnL
- Win rate remains relatively stable across sentiment types

## Strategy Insights
- Reduce trade frequency and risk during Fear periods
- Maintain controlled participation during Greed periods

## How to Run
```bash
pip install -r requirements.txt
