
## Used ARIMA model to predict the water supply by chossing the optimal parameters through Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots.

##### The steps involved in the development of this project: -

1) We first develop a test harness in order to evalute other models.
2) In order to define a baseline of performance, we develop a persistence model Walk Forward Validation 
3) We perform some EDA using Matplotlib and Seaborn.
4) Apply Augmented Dickey-Fuller test to test and remove stationarity. 
    ##### Analysis of the time series data assumes that we are working with a stationary time series. The time series is likely non-stationary. We can make it stationary by first differencing the series and using a statistical test to confirm that the result is stationary. This is the Augmented Dickey-Fuller test.
5) We plot the ACF and PACF plots in oprer to determine the optimal parameters for modelling.
6) Modeling with ARIMA (p,d,q)
7) Hyperparameter tuning with GridSearch
8) Model Validation
![Results](https://user-images.githubusercontent.com/52730843/199085070-eb9d7060-989b-46b1-806f-a7600ffe350a.jpg)
