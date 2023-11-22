# SurpriseHousingAssignment
## Table of Contents
* [Problem Statement](#problem_statement)
* [Solution](#solution)
* [Conclusions](#conclusions)
* [Programming Language Used](#programming-language-used)
* [Acknowledgements](#acknowledgements)
## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.

Target Variable is the SalePrice.

## Solution
Linear Regression Model has been used to implement a solution to the problem statement.

## Conclusion
Based on the analysis it is found that the Significant variables in predicting the price of a house and how well those variables describe the price of a house:
 
- GrLivArea	  :Above grade (ground) living area square feet also has significant increase in the sales price.
- MSZoning_FV :Floating Village Residential also has significant effect in the sales price.
- OverallQual : Quality of over all house also has significant increase in the sales price.
- MSZoning_RL : Residential Low Density is good then it will also has significant effect on sales price.
- Foundation_PConc: Poured Contrete foundation has also significant impact on the sales price
- TotalBsmtSF	:Total square feet of basement area is also a reason to increase in salesprice
- OverallCond : If the Overall Condition is Excellent the SalePrice is higher
- SaleType_New : If New is sold then higher sale price
- SaleCondition_Normal: Normal Sale when compared to othersales has an improvement in the sales price
- Neighborhood_NridgHt: Sale price is high if in Northridge heights neighborhood

 If the customer starts to focus on these variables they can notice significant increase in the sales price.
 
##### The optimal alpha value in case of Ridge and Lasso is as below:

- Ridge - 3.0
- Lasso - 0.0001


Also, based on the model comparison results, we notice that Lasso regression model has slightly higher R2 Scores and slightly lesser MSE value compared to Ridge Model. This suggests that the Lasso regression model is performing better in terms of prediction accuracy on your specific dataset.

Therefore, the variables predicted by Lasso in the bar chart(in the Jupyter notebook) as significant variables for predicting the price of a house.

## Programming Language Used
Python

## Acknowledgement
- This project was based on Upgrad course on ML 


## Contact
Created by [Sarita Behera](@saritab07) - feel free to contact me!
