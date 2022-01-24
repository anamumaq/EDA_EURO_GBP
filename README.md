# EDA_EURO_GBP
Historic Price of the pair Euro Libra EDA

## From Hack The Markets - EDA

### Background
Christine Lagarde is the president of the European Central Bank and was the managing director of the International Monetary Fund. After Brexit, the European Central Bank feared the implications that this separation could have for the European financial industry, that is why to improve their future decision making they have decided to create a system that allows them to estimate the valuation of the European currency with that of the Pound Sterling going forward. For this reason, the European Central Bank needs you.

### Dataset
A dataset of historical information on the EURO-LIBRA pair is provided.
A currency pair is the dyadic quotation of the relative value of a currency unit against the unit of another currency in the foreign exchange market.

For example: EURGBP = 0,9 means that 1 EURO has a value of 0,9 GBP.

Historical prices in the dataset goes from January 3rd 2000 to Octobre 29th 2019.

The information is given on a weekly timeframe, i.e. each row of the dataset corresponds to 1 week. The dataset contains 8 predictor variables.

The predictive variables of the dataset are:

* ‘Open’: Price of the pair at the beginning of the day.
* ‘High’: Maximum price that the pair reaches during the week.
* ‘Low’: Minimum price that the pair reaches during the week.
* ‘Close’: Price of the pair at the end of the week.
* ’rsi’: Relative Strength Index, is an indicator that is often used in technical analysis and shows the strength of the price.
* ’ema_fast’: Exponential Moving Average taking the average value of 14 weeks.
* ‘ema_slow’: Exponential Moving Average taking the average value of 42 weeks.

The moving averages are usually used to detect trends in the markets, when the fast moving average (ema_fast) exceeds the slow moving average (ema_slow) indicates the beginning of an uptrend.

* ‘volatility’: Volatility is a measure of the intensity of changes in the price of an asset. In this case the volatility has been obtained from the NATR (Normalized Average True Range).
