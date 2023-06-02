# PLprediction
This project focuses on predicting the outcomes of football matches in the English Premier League
The objective is to select the best model for predicting the results of specific matches using binary logistic regression. The dataset used in this project consists of the latest seasons of the Premier League obtained from the football-data.co website.

Project Description
The project involves the following key steps:

Data Preparation:

Selection of relevant seasons for analysis, considering factors such as recency and data availability.
Identification and retention of essential variables for further exploration.
Labeling the match results as "L" (home team wins) or "V" (away team wins) and removing matches resulting in a draw.
Feature Engineering:

Expansion of the feature space by creating interactions between predictors, such as xi × xj and xi/xj, and applying common transformations like logarithm (log(xi)) and exponential (exp(xi)).
Exploration of additional predictive variables using machine learning tools and external sources. Sources and conclusions should be documented.
Model Selection:

Selection of an appropriate performance metric based on the goal of predicting football matches for betting purposes, along with a justification for the choice.
Application of Best Subset Selection (BSS) to identify the best logistic regression model considering different numbers of variables, using the selected performance metric and 10-fold cross-validation.
Evaluation of the models using Step-by-Step Forward Selection (FWD) and comparison with the BSS approach.
Final selection of the preferred strategy and prediction of match outcomes for the out-of-sample matches listed in the table.
Latent Variables:

Using the design matrix X obtained from the previous analysis (refer to question 3.d), construction of a reduced design matrix Z that captures more than 80% of the original data variability. The number of variables required to achieve this objective should be determined.
Prediction of match outcomes for the out-of-sample matches using the reduced design matrix Z.
The aim of this project is to showcase your skills in data preparation, feature engineering, model selection, and prediction using machine learning techniques. By successfully completing this project and sharing it on your GitHub, you can demonstrate your proficiency in handling real-world datasets and developing predictive models for football match outcomes.




