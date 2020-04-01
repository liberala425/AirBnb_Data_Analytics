# AirBnb_Data_Analytics
AirBnB is a popular way for traveling in recent years. We are curious about the different prices in different cities. By analysis AirBnb prices for Seattle and Boston, we can get some ideas about it.

## Data Description
Data is from Kaggle. There are two datasets, one is for Seattle, the other one is for Boston.

https://www.kaggle.com/airbnb/seattle

https://www.kaggle.com/airbnb/boston

Both datasets contain three files: 
1. listing.csv 
2. calendar.csv 
3. review.csv

## Required Libraries
* pandas
* numpy
* matplotlib.pyplot
* sklearn.linear_model
* sklearn.model_selection
* sklearn.metrics
* os
* seaborn

## Analysis Steps
Using Jupyter Notebook to perform the analysis.

1. Analyse which neighbourhoods are popular by counting the number of listings in each neighbourhood and retrive the top 15         neighbourhoods in Seattle and Boston
2. Analyse what time of the year are the busiest or peak time by adding _month_ and _weekday_ column, calculating average prices for each month and weekday. The higher the price, the busier the time is.
3. Analyse what factors affect or contribute to the Airbnb listing price by building a linear regression model. By sorting the coefficients, we can see which factors affect the price.

## Summary of the Analysis
By using groupby method, we get to know the popular neighbourhoods and peak time in Seattle and Boston. Building a linear regression moel, we get to know the listing of factors contribute to the price.

## Blog Post
A detailed blog post on medium.com.

https://medium.com/@liberala425/airbnb-prices-analyses-for-seattle-and-boston-ca987f05acf2
