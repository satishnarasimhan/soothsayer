# Soothsayer

Soothsayers in the medieval age used to go around predicting a future event.

This program uses LSTM to predict the stock's price movement over the near term.

Data is obtained from Yahoo Finance (yfinance package) for the symbol provided.
A subset of the inputs is used to train the data and the remainder are used to test the prediction.

Graphs will plot the prediction against the actual (on the remainder data set). Similarly the graph will provide the prediction for the near future.

Outcomes
------------
Stock price predictions too far into the future are perilious. The accuracy of the prediction is limited to the immediate future in terms of the timeline.
However, the same model will be highly accurate when it comes to movements of a cyclical nature.
