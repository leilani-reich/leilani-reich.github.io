---
layout: project
type: project
published: true
image: img/projects/house-price-predictions-square.png
title: House Price Predictions
permalink: projects/house-price-predictions
# All dates must be YYYY-MM-DD format!
date: 2022-05-11
labels:
  - Machine Learning
  - Kaggle
  - Python
  - Jupyter Notebook
summary: I created a machine learning model to predict the prices of homes in Ames, Iowa for the Kaggle competition titled "House Prices - Advanced Regression Techniques."
---
## Overview

I built a machine learning (ML) model to predict the prices of houses in Ames, Iowa, for a competition on Kaggle, a Data Science and
Machine Learning website. The dataset I used to create my ML model provided data on 79 explanatory variables describing some aspect of the homes, such as
the year built and lot frontage. This project enabled me to gain a deeper understanding of the machine learning process: preprocessing data, splitting the dataset, model selection,
hyperparameter optimization, and model evaluation. I worked on my model in the Jupyter Notebook IDE and utilized the SciKit Learn, Pandas, NumPy, Keras,
and XGBoost libraries. 

<img class="ui image" src="../img/projects/house-price-predictions-long.png" height="300" width="800">

## Process

To begin the project, I used SciKit Learn's SimpleImputer to impute missing data so that all the data had some real value close to the average in
the dataset. Then, I ordinal encoded categorical data that had an inherent ordering and one-hot encoded all other categorical data. I did this to convert
my categorical data into a numerical form, which will allow it to be used with ML models. Next, I normalized my data to ensure no feature was
getting too much power due to a difference in units across the dataset. Once I finished preprocessing the data, the next step was to split the dataset up
into train and test sets in order to train the ML models and make predictions with them. However, Kaggle already provided train and test sets, so I stuck
with these. I tried four different models for this project: the RandomForestRegressor and GradientBoostingRegressor models from SciKit Learn, the KerasRegressor model from Keras and SciKit Learn, and the XGBoost model from the XGBoost library. After tuning each of these models and evaluating their performance, I selected the XGBoost model as my final model. To optimize the model and find the best hyperparameters, I used different cross-validation techniques including GridSearchCV and RandomSearchCV (from Scikit Learn) and hand-tuning. Finally, once I received a promising score from my cross-validation, I turned in my XGBoost model to Kaggle to evaluate its performance on unseen house prices data. My model achieved an root mean squared log error (RMSLE) score of 0.12361. At the time of my submission, this put me in position 490 out of 4325 on the Kaggle leaderboard, which was the top 11% 
of submissions.

Link to project: [House-Price-Predictions-GitHub](https://github.com/leilani-reich/House-Price-Predictions-Kaggle/tree/main)
