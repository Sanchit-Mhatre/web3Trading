# Web3Trading

This project analyzes historical trading data from multiple cryptocurrency accounts, correlating trade performance (PnL, volume, etc.) with the Crypto Fear & Greed Index. The goal is to identify patterns in trader behavior, such as buy/sell strategies under different market sentiments (e.g., Fear, Greed), classify traders based on profitability, and provide overall performance summaries.


For better Understanig View in code


trading-sentiment-analysis/
│
├── README.md                 # Project overview, installation, usage, etc. (as generated)
├── requirements.txt          # Python dependencies
├── analysis.ipynb            # Main Jupyter Notebook for data loading, cleaning, merging, analysis, and visualization
│
└── csv_files/                # Directory for input datasets
   ├── fear_greed_index.csv  # Crypto Fear & Greed Index data (2,644 rows)
   └── historical_data.csv   # Historical trading data (211,224 rows)
   └── merged_trading_sentiment.csv 
