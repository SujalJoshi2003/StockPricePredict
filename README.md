# StockPricePredict
LSTM Model trained for AAPL stock from 2019 to 2025 for predicting its closing value.


Before you start reading the description I would like to provide the answer that you are looking for - Predicting stock prices just using stastical data is not possible.

Data was fetched from yfinance library , which provided OHCL values for each trading day with volume. Using this data I latter extracted technical metrics like EMA,MACD,Signal Line,and OBV which helps traders in decision making.
The aim was to predict Closing values for the stock. 
Achieved results were amazing , but the only problem was that the model was learning only statstical patterns and important factors like market sentiments , company performance etc was not taken into account which obviously is needed.

