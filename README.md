# Assignment - Advanced Regression
## Assignment Part-I
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
>The company wants to know:
    -Which variables are significant in predicting the price of a house, and
    -How well those variables describe the price of a house.


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
    -Which variables are significant in predicting the price of a house, and
    -How well those variables describe the price of a house.
- The data is provided in the CSV file.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Top 5 variables have best predictability with Lasso Regularization  :

 1. OverallQual	(Overall material and finish of the house)
 2. GrLivArea	(Living area square feet)
 3. OverallCond	(Rates the overall condition of the house)
 4. YearBuilt	(Age of the house)
 5. Total_sqr_footage (Overall square feet of the house)

As the values of these variable increase, the sale prices will increase too

- Optimal value of alpha for Ridge Regression: "2".
- Optimal value of alpha for Lasso Regression: "0.0001".

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - 3.8.2
- Numpy - 1.14.5
- Pandas - 1.1.0
- Seaborn - 0.12.2
- Matplotlib - 3.2.1
- Scikit-learn 1.2.2
- Statsmodels 0.11.0

## Acknowledgements
- This project is a part of the required research for PG Program in ML & AI.
- Theoretical and practical concepts learned from Advanced Regression module are very helpful to address real-world issues.

## Contact
Created by [@changshuren] - feel free to contact me!

## License
This project is open source.

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->