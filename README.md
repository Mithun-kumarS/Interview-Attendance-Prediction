# Interview-Attendance-Prediction
This kernel foretells whether a candidate will attend interview or not based on the candidate location, job skills &amp; other 26 parameters

## About DataSet

Source: https://www.kaggle.com/vishnusraghavan/the-interview-attendance-problem

The Dataset consists of details of 1200 + candidates and the interviews they have attended during the course of the period 2014-2016.

## Data Cleaning

Below are the challenges solved.

last 5 blank columns are dropped

last 1 blank row is dropped

Mergeable_Multiple_categories, Null_values & misspelled_data in the columns are corrected using apply(function)

## Feature Engineering

Converted date into weekdays to better understand the pattern

## ML Models Used

CatBoostClassifier,
Logistic Regression,
Support Vector Machine,
Decision Tree,
Neural Network,
Random Forest,
XGBoost,
LGBMClassifier,
XGBRFClassifier,
GradientBoosting,
GaussianNB,
KNeighborsClassifier.

# Results-

![Untitled](https://user-images.githubusercontent.com/85584749/129439926-2fa577ee-8fd9-4111-8b17-9a4e8523acd1.png)


## Sorted BarPlot of Accuracy

![Untitled](https://user-images.githubusercontent.com/85584749/129439965-7d8baa04-41ce-41db-b07a-a7d3ceff66b6.png)
