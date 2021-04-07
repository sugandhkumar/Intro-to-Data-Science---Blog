## Project Overview 

### Motivation
This project is a requirement for the Data Scientist Nanodegree program. For the project, i chose to work with the Boston Airbnb datset availabe at kaggle.

### Objective
The aim to the analysis is to answer the folloing three questions - 
1. How much does the neighborhood affect the price of the listings in Boston?
2. Which months do we see the highest price for Airbnb listings in Boston?
3. What are the other prominent factors that have an effect on the price that owners are able to charge? e.g. – being a super host, the number of amenities provided etc. 


### Libraries used
1. import numpy as np
2. import pandas as pd
3. import matplotlib.pyplot as plt
4. import seaborn as sns
5. import statsmodels.api as sm
6. from sklearn.linear_model import LinearRegression
7. from sklearn.model_selection import train_test_split
8. from sklearn.metrics import r2_score, mean_squared_error
9. import dataframe_image as dfi

### Files used
1. calendar.csv - This has the price listings an availability of a listing from Sep 2016 - Sep 2017
2. lisings.csv - This has the details of the listings along with other property and host characterstics. The data is as of Sep 2016

### Summary of the analysis
1. We see a strong neighborhood effect on the prices that owners are able to charge for their listing. We also see that some months are more favorable in terms of prices for owners.
2. Apart from neighborhoods, property types and room types also have a high significant impact on the prices. Some host characteristics like how fast do the host responds, whether they are a super host also have an impact on price charged. Some amenities are also associated with higher price, providing avenue for owners to maximize the value from their properties. 
