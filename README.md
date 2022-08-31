# Project Name
> Study on House Price Prediction using Advanced Linear Regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
 -- Which variables are significant in predicting the price of a house, and
 -- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
After comparing both the models we can see that the below 5 features are explaining the given data set:
- MSSubClass_160 - 2-STORY PUD - 1946 & NEWER type of dwelling involved in the sale
- Total_sqr_footage - Overall area for all floors and basement
- MSSubClass_70 - 2-STORY 1945 & OLDER type of dwelling involved in the sale
- EnclosedPorch - Enclosed porch area in square feet
- PoolArea - Pool area in square feet
- Best alpha value for Lasso : {'alpha': 0.0001}
- Best alpha value for Ridge : {'alpha': 0.0001}.

## Technologies Used
- python library - version 3.9.7
- numpy library - version 1.20.3
- pandas library - version 1.3.4
- matplotlib library - version 3.4.3
- seaborn library - version 0.11.2
- jupyter notebook - server version 6.4.5
- sklearn

## Acknowledgements
- This project was inspired by study on House Price Prediction system.

## Contact
Created by [@pradeeproy303] - feel free to contact me!

## License
This project is open source.
