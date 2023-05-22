# Housing price prediction with Lasso and Ridge regularisation
> Problem statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression..


## Table of Contents
* Data Understanding/Cleaning, Univariant/Bivariant analysis/Data Visualisation/Building a linear module with all the variables/Residual Analysis of the train data/Model Evaluation/Calculating R-squared score on test data/Lasso and Ridge regularisation
* Numpy,Pandas, Matplotlib, Seaborn and Sklearn libraries used
* conclusions
* Course Lectures

<!-- You can include any other section that is pertinent to your problem -->

## General Information
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
- The R-squared score on predicted data from test dataset is 0.797 for Linear, 0.798 for Ridge and 0.8006 for Lasso Regression.

- From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 80% of House price prediction. 

- The top 10 variables based on the coeffiencients selected inorder and significant in predicting the house prices are.
    
    __For Linear and Ridge Regression:__
    OverallQual_10, LotArea, OverallQual_9, OverallQual_8, MasVnrArea, KitchenAbvGr, 3SsnPorch, OverallQual_7, OverallCond_9, 
    LowQualFinSF
     
    __For Lasso Regression:__
    OverallQual_10, OverallQual_9, LotArea, OverallQual_8, MasVnrArea, KitchenAbvGr, OverallQual_7, OverallCond_9, WoodDeckSF, 
    HalfBath   
    

- The optimal value of lambda for Ridge is 0.2 and for Lasso regression is 0.0001.
    
- Using Linear regression, we can predict the house price with 0.79% confidence.
- Using Ridge regression, we can predict the house price with 0.79% confidence.
- Using Lasso regression, we can predict the house price with 0.80% confidence.


## Technologies Used
- numpy - version 1.21.5
- pandas - version 1.4.4
- Seaborn - version 0.11.2
- Matplotlib - version 3.5.2
- Sklearn - version 3.8
- Python - version 3


## Contact
Created by [ailaveninareshkumarailaveni@gmail.com] - feel free to contact me @+91-9972423009.
