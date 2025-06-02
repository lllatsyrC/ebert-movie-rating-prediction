# The Roger-Ebert Bot

ML Regression Project

## Goal

The goal of this project is to use linear regression model to predict the renowned late movie critic Roger Ebert's film rating if he were alive today. My primary and secondary datasets were obtained through webscraping process. Using numerical and categorical features, along with some feature engineering, I built some linear regression models. After multiple trials of 5-folds cross-validation test, modifying datasets, and more feature engineering, my final linear regression model with lasso regularization has R-squared value of 0.396 and mean absolute error of 0.55, which in layman's term, the prediction is off by 0.5 star. 

To learn more, see my [blog post](https://crystalhuang-ds.medium.com/the-roger-ebert-bot-regression-project-bae0228d6acf) and  [presentation slides](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/Regression%20Presentation.pdf). 

## Workflow
1. Data Acquisition <br />
    a. [Ebert Data](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/1A_Data%20Acquisition%20(Ebert%20Data%20Scraping%20%26%20Cleaning).ipynb)<br />
    b. [Other Data](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/1B_More%20Data%20Acquisition%20and%20Cleaning.ipynb)<br />
2. [EDA & Feature Engineer & Selection](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/2_EDA%20%26%20FE%20and%20Selection.ipynb)
3. [Regression Modeling & Testing](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/3_Modeling_%26_Testing.ipynb)<br />
    a. [More Feature Engineering](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/3a_More%20FE%20and%20Selection.ipynb)<br />
4. [Attempt on Random Forest Regressor](https://github.com/lllatsyrC/ebert-movie-rating-prediction/blob/main/4_Random%20Forest%20Regressor%20Attempt.ipynb)

## Technologies

- BeautifulSoup
- Selenium
- Python (Pandas, numpy, pickle)
- Matplotlib
- seaborn
- scikitlearn
- statsmodel
