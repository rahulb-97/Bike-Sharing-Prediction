# Bike-Sharing-Prediction
Analyze dataset and develop a linear regression model for a Bike Sharing Company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it.
- This bike can then be returned to another dock belonging to the same system.
- Business goal is to model the demand for shared bikes with the available independent variables


## Conclusions
- After Cleaning the dataset, the features selected for modeling are ['season', 'yr', 'mnth', 'weekday', 'weathersit', 'day_type', 'atemp', 'cnt']
- Dummy values are created for categorical columns and first columns are dropped to reduce data
- Our Multiple Linear Regression model fit data and predicts cnt (target) variable (cnt) with r2_score = 0.8133 (81.33% accuracy)

## Technologies Used
- python - version 3.11
- pandas - version 2.2.2
- numpy - version 1.26.4
- matplotlib - version 3.8.4
- seaborn - version 0.13.2


## Contact
Created by [@rahulb-97] - feel free to contact me!
