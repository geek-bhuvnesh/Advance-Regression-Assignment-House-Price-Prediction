## Advance-Regression-Assignment-House-Price-Prediction


> You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

### Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal:
 You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

### Problem solution

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis(EDA)

>  Univariate Analysis,
>  Bivariate Analysis.

- Machine Learning Model

> Feature Selection
> Train Test Split,
> Training the model,
> linear regression
> Advance regeression
  - Ridge
  - Lasso 

- Conclusion

## Conclusion(Inferences):
 - We choose the Lasso Regression model as it achieves similar accuracy with fewer variables, making it a more efficient choice compared to the Ridge regression model
 - Based on the r2_score of the 3 models, we can see that their r2_scores are almost similar, as such it is better to go for the simplest model. In this case it would be better to go with Lasso as it panalizes the variables, and helps in feature selection.
- Optimal value of alpha for Ridge regression : 1.0
- Upon examining the above models, it's apparent that there exists minimal correlation between the Residual and Predicted Value, aligning with our model's expectation of displaying no discernible pattern:

> **The company wants to know:**

**The following variables hold significance in predicting house prices:**

- **BsmtFullBath** : A greater BsmtFullBath area corresponds to a higher SalePrice.
- **LotFrontage:** An increase in the linear feet of street connected to the property area results in a higher price.
- **Overall Condition** : Higher SalePrices are associated with properties in excellent overall condition.
- **Garage Area:** Increased garage area leads to higher SalePrices.
- **CentralAir:** A 'Yes' value for CentralAir is correlated with higher SalePrices.
- **CentralAir**: A 'Yes' value for CentralAir is correlated with higher SalePrices.
- **MSZoning_RH**: Houses near residential areas command higher SalePrices.
- **Overall Quality**: Properties in excellent overall condition tend to have higher SalePrices.
- **Exterior1st_CBlock**: If the house's Exterior1st is CBlock, the price tends to be lower.

**How well those variables describe the price of a house:**

These variables offer valuable insights into house pricing and exhibit linear relationships with price, enabling the company to make strategic investment decisions for properties with the potential for higher future SalePrices

## Technologies Used
- Python 3.10.11
- pandas - 2.0.2
- numpy - 1.24.3
- matplotlib - 3.7.1
- scipy - 1.8. 0
- seaborn - 0.12.2
- sklearn - 1.3.0
- statsmodels - 0.14.0

## Acknowledgements

- https://www.kaggle.com/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://scikit-learn.org/
- https://matplotlib.org/
- https://scipy.org/
- https://pypi.org/project/statsmodels/

## Contact

Created by [@geek-bhuvnesh] feel free to contact us!
