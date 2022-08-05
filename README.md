# Advanced_Regression_Housing_Price_Prediction

# Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

# The company wants to know:
Which variables are significant in predicting the price of a house and How well those variables describe the price of a house.

# Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Steps:-
1)Read and Understand the data

2)Data Exploration
- Univariate Analysis
- Bivariate Analysis

3)Feature Engineering

4)Data Preprocessing
- Missing Value Treatment
- Dummy Variable Creation
- Outlier Treatment

5)Model Building, Tuning & Evaluation
- Split the Data into Dependent and Independent variables
- Train - Test Split
- Scaling numerical columns
- Model 1: Ridge Regression
- Model 2: Lasso

6)Comparing the two models

7)Inferences for 'Surprise Housing'

# Conclusion
The variables significant in predicting the price of a house are: -
- GrLivArea
- OverallQual_9
- OverallCond_9
- OverallQual_8
- Neighborhood_Crawfor
- Functional_Typ
- Exterior1st_BrkFace
- SaleCondition_Alloca
- CentralAir_Y
- TotalBsmtSF
- Neighborhood_Somerst
- TotalBsmtSF and
- Condition1_Norm
- How well those variables describe the price of a house?
- Here will see only top few variables:-

GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.09 to 1.11 times

OverallQual_9 & OverallQual_8: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.08 to 1.13 times

Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.07 to 1.09 times

Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 to 1.08 times

Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.07 to 1.08 times.

In a similar manner, we can deduct how well each variable describes the price of a house.
- Optimal value of lambda for Ridge Regression = 10
- Optimal value of lambda for Lasso = 0.001
