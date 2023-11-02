# time-series-analysis-craigslist-vehicle-datset

Using the Craigslist Vehicles Dataset available on Kaggle [https://www.kaggle.com/datasets/mbaabuharun/craigslist-vehicles], we'd like you to create a Time-Series Model following the approach outlined below.

Here are the key steps:

1. We address the missing values in the dataset. You can handle this by filling in missing values with the median for numerical columns and the mode for categorical columns.
2. We ensure that the data types of the columns are appropriate. Specifically, make sure to convert the 'posting_date' column to a datetime data type.
3. We utilize the 'posting_date' column to create a datetime index for the dataset. This will facilitate the analysis of temporal patterns.
4. With the clean data, we explore it using various visualizations and statistical analysis techniques. This step is crucial for understanding temporal patterns, identifying seasonal trends, and analyzing demand-supply dynamics by region and vehicle type.
5. We build the time-series chart using the ARIMA model with the original and fitted values.
