# StockPricePrediction
Model to predict the 'close' value of the next day given the stocks (IBM-Stocks) of all days until the current day, and developed a front-end UI (Web app) that can help traders invest the right amount of money.

# Technologies Used:
* Python
* Flask
* Heroku
* HTML

# Dataset:
https://www.alphavantage.co/query?function=TIME_SERIES_DAILY&symbol=IBM&apikey=HVVN19TCDTJCN9NE

# Features:
* User can predict the close price for IBM_stock_price_daily.
* We added totally four attributes Open price, High Price, Low Price, Total Volume(in Lacs) for predicting **Close Price.**
* We created two ML models for better understanding for users:
**i) LSTM model (main_model)
ii) Other ML Techniques (SVM, Linear Regressor)**
* The user can upload any stock price values of IBM to predict the present day close price.
* When the values are entered, oru LSTM-model will be triggered and predict the close price.
* We created the code for every company stock prices.
**For example : Instead of IBM_stock prices, we can train the other companies(Google,Tesla,Netflix etc.,) stock price with the help of our code.**
