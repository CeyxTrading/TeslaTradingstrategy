# TeslaTradingstrategy

A simple strategy.
The main components of the project are as follows:

Obtain daily stock price data for Tesla.
Compute Stochastic RSI and Bollinger Bands indicators.
Generate Long/Short signals with a holding period of 3 days based on the calculated indicators.
Create visualizations to display the cumulative returns of the trading strategy.

The strategy formulation and backtesting process involves the following criteria:

A LONG signal is generated if the Close Price exceeds the Upper Bollinger Band AND the Stoch RSI K line is higher than the Stoch RSI D line.
A SHORT signal is generated if the Close Price falls below the Upper Bollinger Band AND the Stoch RSI K line is lower than the Stoch RSI D line.
The holding period for each signal is 3 days.

    If the (Close Price > Upper Bollinger Band) AND (Stoch RSI K line > Stoch RSI D line) we get a LONG signal.
    If the (Close Price < Upper Bollinger Band) AND (Stoch RSI K line < Stoch RSI D line) we get a SHORT signal.
    
    
