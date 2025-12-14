Trader Behavior vs Market Sentiment (Fear vs Greed)

Overview  
This project looks at how trader behavior relates to market sentiment, specifically Fear versus Greed. It uses historical trading data and the Bitcoin Fear & Greed Index. The goal is to understand how profitability, trade size, and risk characteristics shift across different sentiment periods. It also aims to identify behavioral patterns that can lead to better trading strategies.

Datasets  
1. Bitcoin Market Sentiment (Fear & Greed Index)
   - Fields: Date, Classification (Fear / Greed)  

2. Historical Trader Data (Hyperliquid) 
   - Fields used: account, symbol, size, side, time/date, Closed PnL  

Methodology  
- Converted trade timestamps and sentiment dates to daily formats.  
- Merged trader activity with market sentiment based on date.  
- Created features like profitability flags and absolute trade size.  
- Compared trader behavior during Fear and Greed using descriptive statistics and visual analysis.  

Key Insights  
- Traders tend to increase trade size during Greed periods.  
- Larger trades during Greed come with higher PnL volatility and lower average returns.  
- Fear periods show more cautious behavior and relatively stable results.  
- More trading activity during Greed does not improve win rates.  

Outputs  
- `notebook_1.ipynb`: Complete analysis in Google Colab.  
- `sentiment_summary.csv`: Summary of sentiment-based statistics.  
- `pnl_distribution.png`: PnL distribution comparison between Fear and Greed.  
- `ds_report.pdf`: Detailed findings, interpretations, and trading implications.  

How to View  
- Open `notebook_1.ipynb` using the provided Google Colab link (view-only access).  
- https://colab.research.google.com/drive/1jgpoyCYteCPtUy9ruCH73AYshpEMAMAo?usp=sharing
- Refer to `ds_report.pdf` for a summarized explanation of results.  

Author  
Nandini R

 

