# Summary of my projects
Below are brief descriptions and links to various portfolio projects I have completed. These projects show my ability to gather, clean, explore, and understand data, as well as use statistics and machine learning models with visualizations to draw interesting conclusions and make predictions from the dataset. Please contact me if you have any questions or would like to speak further.

<b>1. Predicting Wide Receiver Fantasy Football Scores:</b> https://github.com/mborysiak/Predicting-Wide-Receiver-Fantasy-Points

This project aims to predict the fantasy football scores of NFL wide receivers. It scrapes individual player receiving and team passing data from pro-football-reference.com and average draft position data from myfantasyleague.com for the 1998–2016 seasons. The data is cleaned and merged prior to feature engineering. The final dataset is used for training and cross-validated 5 model (Ridge, Lasso, KNN, RandomForest, and XGBoost). The ensemble predictions on holdout data are compared to actual performance, as well as conventional rankings.  All work was performed independently.

<b>2. Classifying Trip Distance for Bike Ride Share:</b> 

This project classifies the distance a user will ride a bike when using the Chicago-based Divvy Bike share program. Divvy makes trip datasets publicly available on their website: https://www.divvybikes.com/system-data. Using this data, I analyzed various feature transformations and machine learning algorithms in order to predict whether or not a user will ride less than or greater than 2 km for each trip, using only information that would be known at the beginning of the ride. The best model (Light GBM) provided 66% accuracy score on unseen data.

<b>3. Predicting Home Prices in Aimes, IA (Kaggle Competition):</b> https://github.com/mborysiak/Predicting-Ames-Housing-Prices

I completed this project as part of a Kaggle competition (see here: https://www.kaggle.com/c/house-prices-advanced-regression-techniques). I visualized the various aspects of the dataset, removed outliers, cleaned null values, performed feature engineering, and optimized model parameters through a grid search. I created an ensemble model consisting of the Extreme Gradient Boosting (XGBoost) decision tree algorithm and Ridge Regression. The ensemble predictions placed in the ~15% of Kaggle entries at the time of submission (out of 2400 entries).

<b>4. Time Series Forecasting with ARIMA and LSTM:</b> https://github.com/mborysiak/Time-Series-Forecasting-with-ARIMA-and-LSTM

Using various Google Trends and S&P 500 historical data, I compared the performance of AutoRegressive Integrated Moving Average (ARIMA) and Long Short-Term Memory (LSTM) models for forecasting time series data. I also examined how using Gaussian filtering could help improve the predictions on out-of-sample data. Search trends explored include LeBron James, Olympics, Kentucky Derby, colbrew, Zika virus, and Gilmore Girls.

<b>5. Analysis of Teen Birth Rates:</b> https://github.com/mborysiak/Factors-Affecting-Teen-Pregnancy-Rate

This project looked at over 50 factors that could potentially contribute to teen birth rates in various states. The most important factors for predicting teen birth rate on a state-level were determined using a (regularized) linear regression model. I gathered, cleaned, and analyzed the data independently. 

<b>6. Analysis of SAT scores in New York City:</b> https://github.com/mborysiak/Analysis-of-SAT-Scores-in-New-York-City

This project gathers, cleans, and combines data from various sources into a coherent database for exploring predictors of SAT scores for students in New York City. I began this project as part of the DataQuest (dataquest.io) Data Science program, before extending the analysis to include linear regression modeling with regularization.
