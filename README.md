# Predicting Professional Tennis Players' Prize Money
A statistical analysis and machine learning project predicting professional male tennis players' career prize money using age and best career ranking from publicly available data on the top 500 players.

## Overview
This project explores the relationship between age, best career ranking, and total career prize money among professional male tennis players. Using publicly available data from the top 500 players, we developed and evaluated a k-nearest neighbours (KNN) regression model to predict career prize money and investigated the limitations of using ranking and age as predictors.

## Methods
1. Data wrangling & cleaning: processed publicly available performance data on the top 500 professional tennis players into a tidy format suitable for modeling
2. Exploratory data analysis: visualized relationships between age, ranking, and prize money to identify which variables were most influential before modeling
3. Model development: implemented a k-nearest neighbours regression model in R to predict prize money from age and best career ranking
4. Model evaluation: used cross-validation to tune model parameters (k) and compared evaluation metrics (e.g. RMSE) to select the best-performing model

## Key Findings
- Best career ranking was more strongly associated with total career prize money than age. Players with rankings closer to #1 generally had higher prize money earnings.
- Players between ages 30-40 had the highest average total prize money, suggesting that experience and career longevity may contribute to higher earnings.
- The KNN regression model achieved a test error of approximately **$2.94 million**, reflecting the large variability in prize money among highly ranked players.
- The model was most reliable for players between approximately ages 20–32 and those outside the top 10 in best career ranking. Predictions became less stable for highly ranked players with unusually high earnings.
- Using only age and best career ranking limited prediction accuracy. Factors such as tournament performance, weeks spent at a high ranking, injuries, sponsorships, and marketability could improve future models.


Developed for DSCI 100 at the University of British Columbia.
