# Seoul Bike 🚴‍♂️ Sharing Demand Prediction

## Project Information
> We will be predicting rental bike count changes with respect to various changes in environmental factors such as temperature, rainfall, holiday etc. 
> Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. 
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information. 

## Data Information

The dataset has been downloaded from <a href='https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand'>link</a> 
This is an archived dataset from UC Irvine
#### Data Attributes
Additional Information

* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius 
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## Data Analysis
I will be testing these different regression models:
1. LinearSVC
2. RandomForestRegressor
3. Linear Regression
4. ElasticNet
5. Lasso

## To Do:
1. as a first pass then use hyperparameter tuning on the RandomForestRegressor to find the optimal parameters. After applying a GridSearchCV we will see the increase in the metrics (R2, MAE, MSE). 
2. Check for multicolinearity

