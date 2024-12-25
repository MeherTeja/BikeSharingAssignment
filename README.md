# BikeSharingAssignment
build Multiple Linear Regression to predict the demand for shared bikes

# Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

## Key Questions
1.Which variables are significant in predicting the demand for shared bikes.
2.How well those variables describe the bike demands

## Technologies Used
## Libraries Used
## 1. Pandas
Pandas is used for data visualization and data frame
## 2. Matplotlib
pyplot in this Matplotlib is used for visualizing data in graphs, bar charts, histplots
## 3. Seaborn
seaborn is built on top of matplotlib , used for creating statistical graphs 
## Regression Libraries
## 4. from sklearn.model_selection import  train_test_split
splits the dataset into training and testing
## 5. from sklearn.preprocessing import MinMaxScaler
scaling the data between 0 and 1
## 6.from sklearn.feature_selection import RFE
used to select features using Recursive Factor Elimination(RFE)
## 7. from statsmodels.stats.outliers_influence import variance_inflation_factor
used to compute the VIF of features
## 8. from sklearn.metrics import r2_score
used to calculate r2_score
## Conclusions
Factors contributing significantly for the target variables:
1) temp
2) windspeed
3) season_summer
4) season_spring
5) season_winter
6) yr
7) mnth_July
8) mnth_Sept
9) weathersit_Ok
10) holiday

## Acknowledgements
This project was created by me
I took the reference from net
