## Introduction

A series that changes over time is called time series. For consistency and reliability of time series analysis large number of data is required. It ensures that we have good representative sample and effect of noisy data data can be cut out. 

Time series analysis is useful to see how assets and economic variable changes over time.  Finance, retail, and economics related areas require  time series analysis as  currency and sales keep on  changing. 

Some common use case of time series analysis include:
 * Heart rate monitoring
 * Stock price prediction
 * Weather forecast
 * Rainfall measurements


Time frame used in time series can be years, months, weeks, days, hours, minutes and seconds.

When there is need to  analyze data over consistent intervals, time series forecasting is used  to predict the likelihood of future events. Seasonality or cyclic behavior is commonly observed in time series data.


## Components of time series
The various reasons or the forces which affect the values of an observation in a time series are the components of a time series. The four categories of the components of time series are:

-   Trend
-   Cyclic Variations
-   Seasonal Variations
-   Random or Irregular movements

### Trend
The trend shows the  tendency of the data to increase or decrease over  a long period of time.  Trends can  be linear or non-linear (curvilinear). It is a longer-term change.
Some examples of secular trends are:

-   Increase in price of daily consumed goods
-   Increase in pollution level

Thus over  a relatively  long period of time, trend shows if  the data tends to increase or decrease. Trend is  an average, long-term, smooth tendency.  Different sections of time within data  show varying tendencies in terms of trends that are increasing, decreasing, or stable.  There must, however, be an overall upward, downward, or stable trend.

### Cyclic Movements

Cyclic movements are long term oscillations occurring in a time series. These oscillations are mostly observed in economics data and the periods of such oscillations are generally extended from five to ten years or more. These cyclic movements can be studied provided a long series of measurements.
 The cyclical variation is periodic in nature and repeats itself like a business cycle. Phase in cyclic variation are:
 * Peak or Prosperity 
 *  Recession
 *  Trough or Depression 
 *  Expansion

 

### Seasonal variations
Seasonal variations are caused by climate, social customs, religious activities, etc.  For example, traffic on roads in the office and school hours, sales of light  at festivals like Tihar, etc. The main causes of seasonal variations are seasons, religious festivals, and social customs. Thus, seasonal component of a time series is the variation in some variable , lets say like sales, due to some predetermined patterns in its behavior. 

Some other examples include the increase in  the cost of various types of fruits and vegetables increase in rainy season, increase in average daily rainfall  in summer and decrease in winter . The changes which repeat themselves within a fixed period, are also called seasonal variations.

Seasonal effects are different from cyclical effects, as seasonal cycles always occur within one calendar year. But cyclical effects, such as  increased unemployment  can span time periods shorter or longer than one calendar year.

The main difference  between seasonal and cyclical behavior can be figured out by finding how regular the period of change is. A seasonal behavior is always strictly regular. There is a precise amount of time between the peaks and troughs of the data. For instance start of summer and winter season and their span has seasonal behavior.

Cyclical behavior on  can drift over time and  the time between periods isn't precise. For example, the stock market tends to cycle between periods of high and low values, but there is no set amount of time between period of rise andd fall.


### Random or Irregular movements
These are sudden changes occuring in a time series which are unlikely to be repeated. These are the components of a time series which cannot be explained by trends, seasonal or cyclic movements. These variations are sometimes called residual or random components. These variations, though accidental in nature, can cause a continual change in the trends, seasonal and cyclical oscillations during the forthcoming period. Earthquakes,  worldwide COVID pandemic are some examples of  the root causes irregular movements.  
  
## Mathematical representation of time series
Let us represent time by variable `t`  and let  y<sub>t</sub>  be variable under study.

Since  y<sub>t</sub>  is function of time , mathematically we can write:
 y<sub>t</sub> = f (t)

Let the value of variable be  y<sub>1</sub>,y<sub>2</sub>,y<sub>3</sub>,y<sub>4</sub>.....y<sub>n</sub> at times t<sub>1</sub>,t<sub>2</sub>,t<sub>3</sub>,t<sub>4</sub>.....t<sub>n</sub> respectively.

We have three models for time series :
*  Additive Model 
* Multiplicative Model
* Mixed model

## Additive Model
Let us  consider T<sub>t</sub>, S<sub>t</sub>, C<sub>t</sub>, and R<sub>t</sub> as the  trend value, seasonal, cyclic and random fluctuations at time t respectively.

So the value of yt at any time t can be written as:
y<sub>t</sub> =  T<sub>t</sub>+ S<sub>t</sub>+ C<sub>t</sub>+R<sub>t</sub> 

Additive  model assumes that trend value, seasonal, cyclic and random fluctuations  act independently of each other.

## Multiplicative Model

Let us  consider T<sub>t</sub>, S<sub>t</sub>, C<sub>t</sub>, and R<sub>t</sub> as the  trend value, seasonal, cyclic and random fluctuations at time t respectively.

So the value of yt at any time t can be written as:

y<sub>t</sub> =  T<sub>t</sub>× S<sub>t</sub>×C<sub>t</sub>×R<sub>t</sub> 

Thus in multiplicative model, trend value, seasonal, cyclic and random fluctuations in a time series operate proportionately to each other.

## Mixed model

It is formed using various combination of additive and multiplicative models.

An example of combination can be :

y<sub>t</sub> =  T<sub>t</sub>× S<sub>t</sub>+ C<sub>t</sub>×R<sub>t</sub>

Another example of combination can be :

y<sub>t</sub> =  T<sub>t</sub>+ S<sub>t</sub>+ C<sub>t</sub>×R<sub>t</sub>


