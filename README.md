
![header](https://user-images.githubusercontent.com/60201466/167953233-53ce9848-5da5-481b-a14d-270c794255d1.jpg)

Source: Kaggle [H&M Personalized Fashion Recommendations](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/overview)

Data source: Kaggle [Data](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data)

## Files

 articles_EDA.ipynb: EDA for articles dataset

 customers.ipynb: EDA for customers dataset

transaction_train_EDA.ipynb: EDA for transactions dataset

 feature_engineering.ipynb: Feature engineering, model, result
###  Project Overview

Given the purchase history of customers over time, along with supporting metadata, we want to predict what products each customer will purchase in the 7-day period immediately after the training data ends.

##  Model & Result

#### Bagging Classifier
- Accuracy score = 78 %
- Execution time = 2.06 s per test datapoint

#### Light GBM
- Accuracy score = 80 %
- Execution time = 670 ms per test datapoint

#### Neural Network
- Accuracy score = 77 %
- Execution time = 5.5 ms per test datapoint
