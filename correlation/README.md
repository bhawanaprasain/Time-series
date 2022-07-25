## Correlation
Correlation in general help us to find the strength of the relationship between two variables.Correlation can be positive, negative or neutral.

The nearer the value of  correlation to +1, the stronger the positive linear relationship.
The nearer the value of  correlation to -1, the stronger the negative linear relationship.
The nearer the value of  correlation to 0, the weaker the linear relationship.

We define two types of correlation in time series.

1. Auto Correlation
2. Partial Auto Correlation


## Autocorrelation

Autocorrelation (ACF) is the calculation of the correlation of the time series observations with values of the same series, but at previous times. Since its a correlation within same series its named as autocorrelation.

The time steps at those previous times are referred to as lags.


A time series can have different components like trend, cycles, seasonality and residuals. Since ACF considers all these different  components while finding correlations, it’s a ‘complete correlation plot’.


## Partial autocorrelation

Partial Autocorrelation (PACF) calculates the relationship between an observation in a time series with observations at previous time steps, but after eliminating intermediate relations .

So in partial auto correlation, the indirect correlations are removed.

PACF finds correlation of the residuals which remains after removing the effects which are already explained by the earlier lags with the next lag value.  So we terms it as  ‘partial’ and not ‘complete’ already found variations are removed before we find the next correlation. 


Both the ACF and PACF start with a lag of 0, which is the correlation of the time series with itself and so  correlation equals to 1.

The main  difference between ACF and PACF is the inclusion or exclusion of indirect correlations in the calculation  process.


