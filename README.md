# TimeSeries-Forecasting

DataSet Link:- https://www.kaggle.com/competitions/ubiquant-market-prediction/data

This dataset contains features derived from real historic data from thousands of investments. Your challenge is to predict the value of an obfuscated metric relevant for making trading decisions.

# train.csv

row_id - A unique identifier for the row.
time_id - The ID code for the time the data was gathered. The time IDs are in order, but the real time between the time IDs is not constant and will likely be shorter for the final private test set than in the training set.
investment_id - The ID code for an investment. Not all investment have data in all time IDs.
target - The target.
[f_0:f_299] - Anonymized features generated from market data.

example_test.csv - Random data provided to demonstrate what shape and format of data the API will deliver to your notebook when you submit.

example_sample_submission.csv - An example submission file provided so the publicly accessible copy of the API provides the correct data shape and format.

supplemental_train.csv - Once submissions are locked on April 18th, this file will be replaced with the data currently used for the public leaderboard. Until then it will contain randomly generated noise of the correct shape to assist with debugging.

ubiquant/ - The image delivery API that will serve the test set. You may need Python 3.7 and a Linux environment to run the example test set through the API offline without errors.

# Result
A model that forecasts an investment's return rate. Train and test your algorithm on historical prices. Top entries will solve this real-world data science problem with as much accuracy as possible
