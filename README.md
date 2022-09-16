# Stock Price Prediction using LSTM
Downloads adjusted daily returns of a configurable date range and set of stocks from Yahoo Finance, concatenates them all into a long sequence, and trains an LSTM to predict future returns based on the sequence of past returns.

### Specifics
- Implemented in TensorFlow, adapted from Google's PTB RNN prediction example
- Returns are normalized using standard deviation (lookback configurable). Positive drift should be negligible.
- Train / validation / test sets are organized in chronological order.

### Dependencies
- TensorFlow
- pandas_datareader
- numpy
