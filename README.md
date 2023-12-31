# House Price Prediction 
Develop regression model using regularization techniques to predict the house price based on dataset provided. <br>


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## General Information

- Problem Statement <br>
  A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

- Business Goal <br>
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- Project Background <br>
  This project is an assignment containing two parts.
  Part-I is a programming assignment (to be submitted in a Jupyter Notebook), and Part-II includes subjective questions (to be submitted in a PDF file). 
- Dataset Used <br> 
  train.csv


## Technologies Used
- Python Libraries Used
  
import numpy as np <br>
import pandas as pd <br>
import matplotlib.pyplot as plt <br>
import seaborn as sns <br>
from sklearn import linear_model, metrics <br>
from sklearn.linear_model import LinearRegression <br>
from sklearn.linear_model import Ridge <br>
from sklearn.linear_model import Lasso <br>
from sklearn.model_selection import GridSearchCV <br>
from sklearn.metrics import mean_squared_error, r2_score <br>
import os <br>
from sklearn.preprocessing import scale <br>
from sklearn.model_selection import train_test_split <br>
from sklearn.metrics import r2_score, mean_squared_error <br>

- Development Tool
 
Jupyter Notebook

- Source Code Repository

Github


## Conclusions
The 5 most significant predictor variables as per Ridge regression model are 
OverallQual, 
GrLivArea,
Neighborhood_NoRidge,
Condition2_PosN,
Neighborhood_NridgHt.

The 5 most significant predictor variables as per Lasso Regression model are
RoofMatl_CompShg,
GrLivArea,
RoofMatl_WdShngl,
RoofMatl_Tar&Grv,
OverallQual.




## Contact
Created by ashandish@yahoo.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
