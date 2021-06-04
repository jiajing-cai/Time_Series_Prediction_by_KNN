# Time_Series_Prediction_by_KNN
Time Series Prediction by using K-Nearest Neighbors method

## Introduction
This project is mainly use K-Nearest Neighbors method to do the prediction. The data set is a time series and related to the “coffee” from Google trends in the past a week. The value I intend to predict is the last hour of this series. Since we can check the actual value from the series, it’s convenient to compare the accuracy of the prediction directly. In order to try different ways for predicting, I used two/three/four dimensional models respectively for the KNN methods.

## Data Preparation and Cleaning
After downloading the dataset from Google trends, the first thing I need to do is data preparation. Since the raw data are only two columns with timeline and numbers of records, I use PivotTable in excel to convert them into muti-dimensions. The result shows in the following figure.
![image](https://user-images.githubusercontent.com/84099960/120742828-b0dff200-c4c5-11eb-990d-62923cb26251.png)


## Result
From the above results, the most accurate predictions under different dimensions models are all generated when K is 4. In conclusion, KNN is a good prediction method, especially when the amount of data is not large enough. The results show that when K=4, the prediction value of the term "coffee" using the KNN method is the most accurate.

