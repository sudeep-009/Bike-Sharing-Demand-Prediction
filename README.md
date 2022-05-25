# Bike-Sharing-Demand-Prediction

# Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
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

# Understanding Data
* Dataset consists of 8760 records.
* Dataset consists of 14 features.
* Dataset consists of 14 features.
* No Null Values were present in the dataset.


# Approach
* EDA
      1. More demand during the Summer.
      2. Least demand during the Winter.
      3. During the Snowfall the demand of rented bike is less.
      4. Count of Rented Bike during the winter is very less as compared to other season.
 
 * Muliticollinerity
      1. Used VIF for continuous predictors.
      2. Used Chi-Square for categorical predictors.
 
 * Feature Selection
      1. Used Sequential Forward Selection.
 
 * Model training.
      Algorithms Used:
      * Linear Regression
      * KNN
      * Random Forest.
      * XGBoost.
  * Model Evaluation
      * Acheived best accuracy R2-Score of 84.2% from XGBoost after hyperparameter tuning with the help of GridSearchCV.
 

