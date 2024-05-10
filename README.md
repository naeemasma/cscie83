Time Series Demand Forecasting

Problem Statement:

The objective of this project is to come up with the best forecasting model to predict air travel demand. The selected dataset is public data, which is available from data.world(Original Source: San Francisco Open Data). This dataset is a San Francisco International Airport Report on Monthly Passenger Traffic Statistics by Airline from 2005 to 2016. Airport data is seasonal. Hence, any comparative analyses would be performed on a period-over-period basis (such as March 2015 vs. March 2016) instead of period-to-period (such as. March 2015 vs. April 2015). Notably, fact and attribute field relationships are not always 1-to-1. For example, Passenger Counts belonging to Southwest Airlines will appear in multiple attribute fields and are additive, allowing us to draw categorical Passenger Counts for the analyses.

Data Set:
https://data.world/data-society/air-traffic-passenger-data

Value Proposition: 

The forecasting model developed by this project can be used to predict air travel demand. Airline companies need to make informed decisions about pricing, capacity, and other areas of their business to optimize their operations and maximize their profitability. 

We will use the four steps below to find the best forecasting model for predicting the demand for air travel.

1.	Gather Information about data/ Data Pre-Processing

2.	Primary Exploratory data analysis.

3.	Choose and fit the Model. 

4.	Use and Evaluate Model.


1.	Gathering Information about Data/ Data Pre-processing:

Data preprocessing is a fundamental step in cleaning and preparing the data for modeling. It includes handling missing values, removing duplicates, and handling outliers. 
If data is missing at random, related data can be deleted to reduce bias. However, data removal can only be performed if we have enough observations for reliable analysis. We may need to develop reasonable guesses for missing data if the portion of missing data is too high. 

2.	Preliminary Exploratory Analysis:

•	Observations

•	Time-bound data summary

•	Descriptive Statistics: 
 
	Training-Testing split of Time Series: 

		•	Time Series and Dataset Split by Segment.

		•	Time Series & Dataset Split by Region
     

3.	Choose and Fit model: 

The proposition is to use the forecasting model below, depending upon the feasibility, and choose the best-fit model. (We will select options from the list below.)

•	Linear Regression Forecasting Model(Deg=2) with BoCox Transformation

•	ARIMA Forecasting Model 

•	Autoregression Forecasting Model

•	SARIMAX Forecasting Model

•	Prophet Forecast Forecasting Model


4.	Use and Evaluate Model:

•	Train, Test subset: As the data is a time series, the time sequence for the data is maintained.

•	Training the Algorithms: Pass the Data through different algorithms.

•	Algorithm Selection: Based on the MSE in the validation, which results in the minimum error is selected.

•	Future Prediction: Generate the future forecast.
