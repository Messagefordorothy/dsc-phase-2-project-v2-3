# Phase 2 Project Description - Group 11
## Overview
This project focuses on predicting house prices using a multiple linear regression model. 
The dataset contains various features such as the number of bedrooms, bathrooms, square footage of living space, waterfront status, house condition, and grade, among others. 
The goal is to build a model that predicts the value of their homes using some of these features.

## Business and Data Understanding
The King County dataset contains house sale prices from 2014 to 2015. 
The dataset was retrieved from Kaggle and published on 08/25/2016. 
All housing information is public data. 
The stakeholders for this project include real estate agencies, property investors, and individuals looking to buy or sell houses.
These stakeholders are interested in understanding how different factors affect house prices, which can inform their decisions regarding buying, selling, or investing in real estate. 
The dataset provides valuable insights into the housing market, allowing stakeholders to make informed decisions based on market trends and property characteristics.

## Modeling
The modeling process involved preprocessing the data, including handling missing values,visualization,  encoding categorical variables, and feature engineering. 
A simple linear regression was modelled against the highly collerated feature. 
We then split the data into training and testing sets and build a multiple linear regression model to predict house prices. 
The model utilizes various features to make predictions and is evaluated using metrics such as R-squared to assess its performance.

## Regression Results
Three models were created. The simple model provided an R-Squared of 0.492, A multiple linear regression with 26 predictors provided an R- squared of 0.675. The R- squared of a model with  sqft_lot and sqft_above features dropped improved to 0.676.
These scores indicate decent predictive performance, suggesting that the model captures a significant portion of the variance in house prices. 
Hoswever, in all the models, the condition number was avove 100 indicating presence of multi-colinearity.

The model's coefficients provide insights into the relative importance of different features in determining house prices, which can be valuable for stakeholders in the real estate industry.


## Conclusion
Overall, this project demonstrates the utility of multiple linear regression in predicting house prices based on various features. By leveraging data-driven insights, stakeholders can make more informed decisions regarding buying, selling, or investing in real estate. Moving forward, further refinements to the model and additional data sources could enhance its predictive accuracy and provide even more valuable insights for stakeholders in the housing market.






