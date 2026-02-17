# Moving_Average_Trading_Strategy_Backtest
Python-based stock market analysis tool that fetches real NSE data and applies a 50/200 moving average trading strategy. Displays buy/sell signals, colored profit-loss tables, performance metrics, and graphs. Built using Pandas, Matplotlib, and yFinance for basic quantitative finance and data analysis.
NSE Stock Moving Average Strategy (Python Project)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
== Project Overview ==
This project is a simple stock market analysis and trading strategy backtesting tool built using Python.
It fetches real stock data from the internet and applies a Moving Average Strategy to check whether a smart trading rule could have made profit.

== The program also shows: ==
1. Clean colored data tables 
2. Strategy performance 
3. Risk measurement 
4. Graph comparison (Market vs Strategy)
This project demonstrates basic quantitative finance + data analysis skills.

== Features ==
1. Fetch real NSE stock data using Yahoo Finance
2. User can enter any NSE stock symbol (RELIANCE, TCS, INFY etc.)
3. Applies 50-day & 200-day moving average strategy
4. Shows BUY/SELL signals
5. Colored dataframe
6. Green = Profit
7. Red = Loss
8. Strategy return & max drawdown
9. Graph visualization
10. Clean & structured Python code

== Strategy Logic (Simple Explanation) ==

The strategy used is called Moving Average Crossover.
Rule:
If 50-day average price > 200-day average → BUY
Otherwise → Do not buy
Then we check:
Did this strategy make money or not?

== Technologies Used ==
1. Python
2. Pandas (data analysis)
3. Matplotlib (graphs)
4. yFinance API (stock data)
5. Jupyter Notebook

== How to Run This Project ==
Step 1: Install libraries
Open terminal or Jupyter and run:
pip install yfinance pandas matplotlib

Step 2: Run the Python file
python stock_strategy.py

Step 3: Enter stock symbol
Example: [RELIANCE, TCS, INFY, LT, HDFCBANK]


Program will automatically fetch NSE data.

== Output You Will See ==
1. Colored data table (profit/loss)
2. Strategy return
3. Maximum risk (drawdown)
4. Performance graph

== Learning Outcome ==
1. From this project I learned:
2. How to fetch live stock market data using Python
3. How trading strategies work
4. Risk vs return analysis
5. Data visualization
6. Writing clean structured code

== Project Use ==
1. This project can be used for:
2. Learning stock market analysis
3. Beginner quantitative finance
4. Resume/portfolio project
5. Python data analysis practice

== Author ==
Kushal Nayak
MBA (Business Analytics & Marketing)
Aspiring Business/Data Analyst
