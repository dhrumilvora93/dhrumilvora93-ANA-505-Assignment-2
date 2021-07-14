# dhrumilvora93-ANA-505-Assignment-2

Firstly, we define the configuration of the plots, by using graphical parameter function.

getSymbols gets the data for unemployment rate from FRED system. Then we subtract it from 100 to get the employment rate.

using dimnames function set the name of the object as ER

chartSeries to create finantial charts given a timeseries like object

ymd used to convert numeric or string like date into date object for ER


Cleaning and transforming data From FRED System for
National Civilian Unemployment Rate (monthly, percentage)
Manufacturers' New Orders: Durable Goods (millions of dollars)
University of Michigan Index of Consumer Sentiment (1Q 1966 = 100)
New Homes Sold in the US, not seasonally adjusted (monthly, millions)
from line 16-66

Defined multiple timeseries object and only kept the overlapping timeseries range line 70

Plot multiple timeseries in a PDF line 74

Creating new indexes for each Variable for a common date range from start date as March 1997
line - 79 to 89
line 117 to 124 Fitting the data with Arima model

line 126 - 131 Forecasting national employment reate timeseries with 2 year forecast


line 135 - 142 Fitting the manufactures's durable goods orders with Arima model

line 144 - 147 Forecasting manufactures's durable goods orders timeseries with 2 year forecast


line 152 - 160 Fitting the consumer sentiment  with Arima model

line 162 - 167 Forecasting consumer sentiment timeseries with 2 year forecast


line 171 - 178 Fitting the new home sales with Arima model

line 180 - 185 Forecasting new home sales timeseries with 2 year forecast
line 192 - 197 Granger causality test is a statistical hypothesis test for determining whether one time series is useful in forecasting another

line 200 - 203 saving dataframe as a file


