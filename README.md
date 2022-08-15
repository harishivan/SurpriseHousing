# "Surprising Housing" company entering Australian market
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is looking at prospective properties to buy to enter the market.
- We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not
- The company wants to know:
    > Which variables are significant in predicting the price of a house, and
    > How well those variables describe the price of a house.
- The type of dataset used is a structured dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The most important predictor variables are 'YearBuilt', 'GrLivArea', 'GarageCars', 'OverallQual_8','OverallQual_9'.
- Lasso regression is best suited for the regularization purpose, and best possible alpha is 0.01.
-  R2 is 0.90 for training data and 0.87 for test data.
- GrLivArea, GarageArea features have high positive correlation with the 'Saleprice'
- High positive correlation is seen amongst - TotalBsmtSF & 1stFlrSF, GrLivArea & 2ndFlrSF, GrLivArea & 1stFlrSF

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.9.7
- Pandas 1.4.3
- SCikit- learn 0.24.2
- Seaborn 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was a part of Upgrad's Assignment for Advanced Linear Regression.


## Contact
Created by [@harishivan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->