Autoregression is a time series model in which observations from previous time steps is used as input to a regression equation inorder to predict the value at future time step.


A regression models like linear regression, models an output value based on a linear combination of input values.This technique can be used on time series where input variables are  observations at some previous time steps, called lag variables.
Autoregression analysis is also used in signal processing where a linear predictor estimates the value of each sample of a signal by a linear combination of values at some previous timestamps. 

An AR(1) autoregressive process dpends on the immediately preceding value, while an AR(2) process depends on the previous two timestamps values.

For example:

`y = w0 + w1*X1`
Where y is the prediction, w0 and w1 are coefficients.
Their values are calculated by optimizing the model on training data, and X is an input value.


Similarly we  predict the value for the next time step (t+1) using the observations at the three time steps `t-1` ,`t-2` and `t-3`. Auto-regressive model would look as follows:

`X(t+1) = b0 + w1*X(t-1) + w2*X(t-2) w3*X(t-3)`
The  regression model uses data from the same input variable at previous time steps of same time series, it is referred to as an autoregression which basically means regression of self.

