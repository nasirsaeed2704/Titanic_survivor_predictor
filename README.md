# Titanic_survivor_predictor
An XGBoost scikit learn Decision tree model to predict whether a person survived the titanic or not. I implemented a custom ML pipeline using scikit learn's Pipeline class and custom transformer classes for data preprocessing.

I also created a random forest ml pipeline in order to compare model performance. On the unseen data, Random forest achieved accuracy score of 0.83240 and XGboost achieved accuracy score of 0.85475

Data preprocessing techniques such as One Hot encoding, feature scaling with z normalization, and Imputations have been utilized along with other techniques after performing simple EDA on the data.
