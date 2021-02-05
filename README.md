# POC_projects

Preliminary Analysis:

1. Data Partitioning: Data is partitioned into training data and testing(validation) data. Length of testing data is 60 months. As we can see in the time plot, more irregularity can be seen after 2015, so there is a higher chance of inaccurate modeling and forecasting if we take length less than 60. More than 60 months is not
feasible as our forecasting horizon is just 24 months.


2. Forecasting Horizon: It is taken as 24 months.Export policies need to be reviewed and implemented by taking the reference of forecasted export demand and for which horizon of just 12 months would be less.

Simultaneously, because of the change in economic factors of U.S. and of countries’ which affect export of U.S., it is not feasible to take forecasting period more than 24 months as it will
include uncertainty.

3. Identification of components: It is evident from the time plot that the export data has both trend and seasonality. We can see that the seasonality is increasing with the increase in trend and hence is multiplicative.
          F(t) = Trend*Seasonality*Random
          

3.1 Analysis of time plot:


i. Equally spaced peaks and troughs which indicated the presence of seasonality
ii. Increase in magnitude of seasonality component along with trend. We can observe that the series
is multiplicative
iii. Unusual drop of level in 2015. It seems to be a bit irregular after 2015 in terms of and trend

  
  
  
