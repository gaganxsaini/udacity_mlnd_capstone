## Capstone Project - New York City Taxi Fare Prediction
### Machine Learning Engineer Nanodegree, Udacity

#### Objective

To predict the fare amount for a taxi ride in New York City given the longitude and latitude coordinates of the pickup and drop-off locations, date & time of the pickup and number of passengers. 

Proposal Review Link:

https://review.udacity.com/#!/reviews/1751806


Files:
------

The project contains following files:

1. Data Exploration.ipynb - Contains code used for data cleanup and exploration. It uses first 5,000,000 rows from the data provided on the kaggle.
	
2. Prediction.ipynb - Contains code for training, tuning and predictions for different regression models considered. It used the dataset obtained after cleaning in the code contained in Data Exploration.ipynb.

3. Visualization.ipynb - Contains code that acts upon the output from the final model chosen i.e. RandomForestRegressor.

4. rf_output.csv - The truth values and predictions obtained by the RandomForestRegressor model. It is used in Visualization.ipynb to create free form visualization and also used to calculate R2 Score.



#### Data Set

Data Set is available on Kaggle:
https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data

