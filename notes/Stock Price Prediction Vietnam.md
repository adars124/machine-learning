Technical analysis indicators are: simple moving average (SMA), moving average convergence divergence (MACD), and relative strength index (RSI).

The LSTM algorithm (Long Short-Term Memory) confirms the stability and efficiency in short-term stock price forecasting which is a regressive neural algorithm. It has the ability to distinguish and synthesize the effects of short-term and long-term factors, by giving different weights to each parameter while skipping the memory it considers irrelevant to predict the next outcome.

LSTM introduces memory cell, a unit of computation that replaces traditional artificial neurons in the hidden layer of the network.

The aim of this study is to evaluate the applicability of cyclic neural networks to the problem of price volatility prediction of stocks on the market.

**Fama (1970)** proposed the efficient market hypothesis which determines that the current price of an asset always reflects all prior information available to it immediately.

**Random walk hypothesis** states that a stock's price changes independently of its history. i.e. tomorrow's price of a particular stock will depend only on tomorrow's information regardless of today's price. (**Burton, 2018**)

Technical analysis is a method based on historical data from the market, primarily price and volume. It has the following assumptions:
- prices are determined exclusively by supply and demand relationships
- prices change with the trend
- changes in supply and demand can be identified on the chart
- changes in supply and demand cause the trend to reverse
- the patterns on the chart tend to repeat

Gradient Vanishing problem is the condition when the gradient is small, increasing exponentially, has almost almost no effect on the output.

Conversely, gradient exploding problem is the situation when the gradient is large, multiplying exponentially leads to gradient explosion.

LSTM was introduced by the research of Hochreiter and Schmidhuber (1997). It constitutes of 3 ports which are called input, forget and output ports. The information entering the network of the LSTM, it can be selected according to the rules. Only those information matching the algorithm will be forwarded, and information that does not match will be forgotten through the forget gate.

This gate-based architecture allows information to be selectively forwarded to the next unit based on the principle of the activation function of the LSTM network. These networks are widely used for tasks like Natural Language Processing, and expecially for handwriting recognition.

**Ding et al. (2015)** combined financial time-series analysis and natural language processing.
**Hegazy et al. (2014)** applied ml algorithms like PSO, LS-SVM to forecase S&P 500 stock market.
Stock Price prediction using price data (**Chen et al. 2015**)
Prediction using historical price data in conjunction with stock indices (**Di Persio and Honchar, 2016**)
**Zguge et al. (2017)** combined LSTM with Naive Bayes method to extract market emotional factors to improve predictive performance.

**What is conjugate gradient?**
A mathematical algorithm for the numerical solution of particular systems of linear equations, namely those whose matrix is positive-semidefinite.