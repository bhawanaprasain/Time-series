Moving average is calculated by taking  an average of fixed number of items in the time series which move through the series by dropping the previous  items of the series  and adding the next items in each successive average.

Let y<sub>1</sub>, y<sub>2</sub>,y<sub>3</sub>,y<sub>4</sub>,y<sub>5</sub>......y<sub>n</sub> be the values of variables at time  t<sub>1</sub>, t<sub>2</sub>,t<sub>3</sub>,t<sub>4</sub>,t<sub>5</sub>......t<sub>n</sub> .

y<sub>1</sub>+y<sub>2</sub>+.......+y<sub>k</sub> , y<sub>2</sub>+y<sub>3</sub>.......+y<sub>k+1</sub> are moving totals of `k`.
<br>
If we divide these moving totals by `k` we can get moving average.





## Why do we need moving average ?

Moving averages help in  smoothing out the volatility of constantly changing variables like price in stock market.  This way, short-term fluctuations are reduced, and investors can get a more generalized picture.


## Some problems associated with moving average:

* Noise
If sliding window is small, then all noise won't be removed from the data

* Loss of low value and peak value
Averaging method will not support in capturing low values and peak values associated with original data.

* Identical weighing
Identical weights are assigned to all data points. However this might lead to issue as  the most recent values have more impact on the future in most cases.

