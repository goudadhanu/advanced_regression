## Advanced-Regression-Assignment
Using Ridge and Lasso Regressions

# Problem Statement - Part I 
This assignment contains two parts. 

# Assignment Part-I

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

# The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

# Business Goal :

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.



# Problem Statement - Part II Assignment


Question 1

What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?

Question 2

You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why?

Question 3

After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?

Question 4

How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?




## Problem Solving Methodology
# Data Understanding-
Understanding and working with data dictionary and getting good knowledge of all the columns and their domain specific uses.

# Data Visualization-
Perform EDA to understand various variables. Check the correlation between the variables.

# Data Preparation-
Create dummy variables for all the categorical features. Divide the data to train & Test. Perform Scaling. Divide data into dependent & Independent variables.

# Data Modelling & Evaluation-
Create Linear Regression model using mixed approach (RFE & VIF/p-value). Check the various assumptions. Check the Adjusted R-Square for both train & Test data. Report the final model.

# Data Regularisation -
Lasso and Ridge regression


# Technologies Used
Python - version 3.9.12

Libraries Used
Pandas , Numpy , Matplotlib , Seaborn , sklearn , statsmodels

## Conclusion
Lasso regression works better with the following predictor variables
1. LotFrontage
2. BsmtFullBath
3. OverallCond
4. CentralAir
5. OverallQual
6. Exterior1st_CBlock
7. MSZoning_RH
8. MSZoning_RM
9. Street_Pave
10. GarageQual


# Contributors
Dhanush Kumar B s

## Contact
Created by [@goudadhanu] - feel free to contact me!
