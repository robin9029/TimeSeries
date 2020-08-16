# TimeSeries
Time Series forecasting 

https://www.youtube.com/watch?v=e8Yw4alG16Q
component of timeseries:
Trend: lets say town has build, and a hardware shop build: now the increase in selling , once every one buys the sell will gradually decrease
Seasonal: New year, selling choclate increase on new year eve and can be observed in few years, eg. summer : ice cream demand increase
Irregularties: erratic ,shot duration,: like corona came and can happen erratic, covid medicine has come
Cyclic: don't have any regularaties can happen anytime , and cyclic and much harder to predict 

when not apply time series?
-when values are constant, like sell of coffie in 4 consiquitve month is constant, predict next month is not use time series
- when we have some function f(x) not use time series 

what is stationay ?
Time series is something to predict the future based on past 
1) constant mean
2) constant Variance 
3) Auto covarince should not depend upon time 

Rolling Stastics :plot moving average and see if varies with time : visual techine 

ADFC:(Dickey–Fuller test tests) Assume  Null hypothesis that time series is not stationary, test comprises of Test statistics and some critical value 
if Test statistics < some critical value  : can reject the Null hypothesis and say data is stationary

ACF: auto corelation function 
PACF: partial auto corelation function helps to determine  AR: Auto regressive & MA: moving average 

AR: forcast next timestamp by regressing over previous value
MA: Forcast the next timestamp value by averaging over the previous value 

ARIMA: AutoRegressive Integrated Moving average (AR-I-MA): -for non stationary data -allows to difference the data -Also includes a seasonal differencing parameter for seasonal non-stationary data diff1 & diff2 are to reduce diffreence make data stationary
