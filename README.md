# Machine Learning 2 - Advanced Regression Assignment

> Table of Contents
>
> A housing company based in the US wishes to enter the Australian Housing Market. The company purchases houses at prices below actual value using data analytics. The company then sells them for a profit at a higher price.
>
> The company wishes to identify prospective houses to buy. This analysis is required to build a regression model using regularisation to be able to predict the actual value of the prospective properties and make a decision whetehr or not to invest.
>
> In order to address these goals the company wishes to know two things:
>
> ```
> 1. Which variables are significant in predicting the price of a house, and
> 2. How well those variables describe the price of a house.
> ```
>
> In addition, the analysis is required to determine the optimal value of Lambda for ridge and lasso regression.

## General Information

### The following describes the major steps in performing the analysis:

```
1. Exploratory Data Analysis:
    a. Import the data
    b. Understand the data
    c. Explore the data

2. Data Cleaning

3. Data Preparation for Analysis

4. Model Building:
    a. Build the model
    b. Evaluate the model

5. Observations and Conclusion
```



## Conclusions

- The model was contrructed with Lasso Regression.
- The following variables or features were determined to be themost important:
- |     | Variable     | Coeff  |
  | --- | ------------ | ------ |
  | C   | constant     | 12.154 |
  | x1  | GrLivArea    | 0.123  |
  | x2  | OverallQual  | 0.097  |
  | x3  | OverallCond  | 0.048  |
  | x4  | TotalBsmtSF  | 0.042  |
  | x5  | BsmtFinSF1   | 0.032  |
  | x6  | Fireplaces   | 0.026  |
  | x7  | GarageArea   | 0.025  |
  | x8  | LotFrontage  | 0.012  |
  | x9  | LotArea      | 0.011  |
  | x10 | BsmtFullBath | 0.002  |
  | x11 | WoodDeckSF   | 0.001  |
  | x12 | MSSubClass   | -0.002 |
  | x13 | age_property | -0.004 |
- The final model was developed as follows:
  - Log(Y) = 12.154 + 0.123(x1) + 0.097(x2) + 0.048(x3) + 0.042(x4) + 0.032(x5) + 0.026(x6) + 0.025(x7) + 0.012(x8) + 0.011(x9) + 0.002(x10) + 0.001(x11) -0.002(x12) - 0.004(x13) + Error

## Technologies Used

- Python 3
- Numpy
- Pandas
- Matplotlib
- Seaborn
- sklearn



## Contact

Created by [@floodyc] - feel free to contact me!
