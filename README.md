# Summary of my projects
Below are brief descriptions and links to various portfolio projects I have completed. These projects show my ability to gather, clean, explore, and understand data, as well as use statistics and machine learning models with visualizations to draw interesting conclusions and make predictions from the dataset. Please contact me if you have any questions or would like to speak further. Other than the two Kaggle competitions, all projects were conceived of and completed independently.

<b>1. Analytics: Analyzing Factors Associated with Teen Birth Rates:</b> https://github.com/mborysiak/Factors-Affecting-Teen-Pregnancy-Rate

This project looked at over 50 factors that could potentially contribute to teen birth rates in various states. The most important factors for predicting teen birth rate on a state-level were determined using a variety of feature selection techniques including univariate methods (i.e. correlations) and multivariate techniques (e.g. regularized regression, random forests, boruta). Using these selection approaches, combined with feature engineering and adjusted r-squared analysis, I determined three critical factors that explained >75% of the variance in the teen birth rate response. The methods used in the project are widely applicable for determing significant relationships amongst variables in complex systems.

<b>2. Regression: Predicting Wide Receiver Fantasy Football Scores:</b> https://github.com/mborysiak/Predicting-Wide-Receiver-Fantasy-Points

This project aims to predict the fantasy football scores of NFL wide receivers. It scrapes individual player receiving and team passing data from pro-football-reference.com and average draft position data from myfantasyleague.com for the 1998–2016 seasons. The data is cleaned and merged prior to feature engineering. The final dataset is used for training and cross-validating 5 machine learning models (Ridge, Lasso, KNN, RandomForest, and XGBoost). The ensemble predictions on holdout data are compared to actual performance, as well as conventional rankings.

<b>3. Classification: Classifying Trip Distance for Bike Ride Share:</b> 

This project classifies the distance a user will ride a bike when using the Chicago-based Divvy Bike share program. Divvy makes trip datasets publicly available on their website: https://www.divvybikes.com/system-data. Using this data, I analyzed various feature transformations and machine learning algorithms in order to predict whether or not a user will ride less than or greater than 2 km for each trip, using only information that would be known at the beginning of the ride. The data was supplemented using external API's including GoogleMaps bike-ride distance and Underground Weather information. The best model (Light GBM) provided 66% accuracy score on unseen data with minimal computation compared to non-engineered approaches.

<b>4. Natural Language Processing: Toxic Comment Classification (Kaggle Competition):</b> https://github.com/mborysiak/Predicting-Ames-Housing-Prices

I completed this project as part of a Kaggle competition (see here: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). The goal of the competition was to accurately classify whether a written text statement from the internet contained one of six toxic categories, such as toxic, identity hate, obscence, etc. I utilized two Natural Language Processing (NLP) approaches in order to create an ensemble model with optimal accuracy for text classification. The first utilized various word embedding datasets that were further trained using a Gated Recurrent Unit (GRU) neural network. The second transformed the sentences with term frequency-inverse document frequency (TF-IDF) followed by linear Naive Bayes-Logistic Regression models. The best ensemble placed in the top 25% out of >4000 applicants as of the time of writing.

<b>5. Regression: Predicting Home Prices in Aimes, IA (Kaggle Competition):</b> https://github.com/mborysiak/Predicting-Ames-Housing-Prices

I completed this project as part of a Kaggle competition (see here: https://www.kaggle.com/c/house-prices-advanced-regression-techniques). I visualized the various aspects of the dataset, removed outliers, cleaned null values, performed feature engineering, and optimized model parameters through a grid search. I created an ensemble model consisting of the Extreme Gradient Boosting (XGBoost) decision tree algorithm and Ridge Regression. The ensemble predictions placed in the ~15% of Kaggle entries at the time of submission (out of 2400 entries).

<b>6. Forecasting: Time Series Forecasting with ARIMA and LSTM:</b> https://github.com/mborysiak/Time-Series-Forecasting-with-ARIMA-and-LSTM

Using various Google Trends and S&P 500 historical data, I compared the performance of AutoRegressive Integrated Moving Average (ARIMA) and Long Short-Term Memory (LSTM) models for forecasting time series data. I also examined how using Gaussian filtering could help improve the predictions on out-of-sample data. Search trends explored include LeBron James, Olympics, Kentucky Derby, colbrew, Zika virus, and Gilmore Girls.
