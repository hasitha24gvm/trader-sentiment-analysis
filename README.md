Trader Performance vs Market Sentiment

This project analyzes the relationship between crypto trader performance (Hyperliquid historical data) and the Bitcoin Fear & Greed Index.  
The objective is to uncover hidden patterns, evaluate profitability under different market sentiments, and deliver insights that can drive smarter trading strategies.


Project Structure

├── Trader_Sentiment.ipynb        
├── csv_files/
│   ├── fear_greed_index.csv      
│   ├── historical_data.csv      
│   ├── _clean_sentiment.csv      
│   ├── _clean_trades.csv         
│   ├── agg_by_sentiment.csv     
│   ├── symbol_sentiment_avg_pnl.csv
│   └── position_bucket_performance.csv
├── outputs/
│   ├── pnl_distribution_by_sentiment.png
│   ├── daily_avg_pnl.png
│   ├── daily_sentiment_value.png
│   ├── symbol_avg_pnl_fear_vs_greed.png
│   └── win_rate_by_notional_bucket.png
├── ds_report.pdf                 
└── README.md     

Tech Stack

Python → Pandas, NumPy, Matplotlib

Google Colab / Jupyter Notebook

ReportLab → for generating ds_report.pdf
