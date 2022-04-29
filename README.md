# TradingBot

This trading bot follows several trading strategies in order to automate the process of trading, minimize room for human error, and ensure calculations are done based off of winning strategies that have a high accuracy rate. These strategies can be backtested following the end of the closing day in order to check the continued accuracy of the strategies given the market conditions.

Strategies that will be used:

* Doji Candle
* 8/21 EMA

# Prerequisites and dependencies
## To run the code simply pull the repo and install the following libraries:
```
pip install alpaca_trade_api
pip install flask
pip install flask_apscheduler
```
## Then run the flask app program
```
python trader.py
```

### Note: The demo was made with an alpaca preminium market data subscription that allowed for real-time data. The subscription has since been cancelled and now the current algorithmn runs with a 15 min market data delay as per the free tier of alpaca. 