In this paper we are forecasting the magnitude and the direction of the Credit Spread, which
is the difference of AAA Corporate Bond Yield and 10 – Year Treasury Constant Maturity Yield. We
predicted the magnitude and direction of the credit spread using simple models such as Simple Moving
Average (SMA) and a variant, the Exponential Moving Average (EMA). The SMA and EMA models
hold a strong assumption that the prediction is the average of the past. This property makes them
ineffective in forecasting an arbitrary number of days into the future. Next, we used the ARIMA model,
but it requires stationary data and it does not capture non-linear relations between features. We used a
Hidden Markov Model to find different regime shifts and produce stationary data. However, we were
still not capturing non-linear relations between features. Finally, we implemented different Long ShortTerm Memory (LSTM) models which resolved all the drawbacks of the previous models and
performed the best at forecasting the credit spread
