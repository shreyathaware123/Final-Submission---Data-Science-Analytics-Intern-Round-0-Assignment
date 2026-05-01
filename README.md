# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

## Datasets
- Trader Data (Hyperliquid)
- Bitcoin Fear & Greed Index

## Steps Performed
1. Data Cleaning & Preparation
2. Date Alignment & Merging
3. Feature Engineering (PnL, Win Rate, Trade Count, etc.)
4. Analysis & Visualization
5. Segmentation of Traders
6. Strategy Recommendations

## Key Insights
- Traders perform best during Extreme Greed and worst during Extreme Fear
- Trading activity is highest during Fear conditions
- Long bias increases during Fear, while short activity increases during Greed
- Infrequent traders generate higher PnL per trade, while frequent traders are more consistent

## How to Run
1. Install required libraries:
   pip install pandas matplotlib
2. Open notebook.ipynb
3. Run all cells

## Tools Used
- Python (Pandas, Matplotlib)
- Jupyter Notebook

## Limitations
- Leverage data was not available, so leverage-based analysis was not performed.
