# US-Stocks-2014-2018--prediction-with-Tensorflow
We try to create a model to  predict those stocks that in buy-worthy or not buy-worthy


Content
* This Data repo contains the following datasets (in .csv format):

  - 2014_Financial_Data.csv
  - 2015_Financial_Data.csv
  - 2016_Financial_Data.csv
  - 2017_Financial_Data.csv
  - 2018_Financial_Data.csv
  
Each dataset contains 200+ financial indicators, that are commonly found in the 10-K filings each publicly traded company releases yearly, for a plethora of US stocks (on average, 4k stocks are listed in each dataset).

For each stock, if the PRICE VAR [%] value is positive, class = 1. From a trading perspective, the 1 identifies those stocks that an hypothetical trader should BUY at the start of the year and sell at the end of the year for a profit.
For each stock, if the PRICE VAR [%] value is negative, class = 0. From a trading perspective, the 0 identifies those stocks that an hypothetical trader should NOT BUY, since their value will decrease, meaning a loss of capital.


## Reference
The Financial Indicators of US stocks (2014-2018) dataset which contains **22077 samples**  has been deposited on the Kaggle repository. [Click to go website](https://www.kaggle.com/cnic92/200-financial-indicators-of-us-stocks-20142018)
