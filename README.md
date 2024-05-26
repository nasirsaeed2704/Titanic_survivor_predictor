# Titanic_survivor_predictor
An XGBoost scikit learn Decision tree model to predict whether a person survived the titanic or not. Implemented using a custom ML pipeline using scikit learns Pipeline class and custom transformer classes for data preprocessing.

A random forest ml pipeline has also been created in order to compare performance. 
On the unseen data, Random forest achieved accuracy score of 0.83240 and XGboost achieved accuracy score of 0.85475

Data preprocessing techniques such as One Hot encoding, feature scaling with z normalization, and Imputations have been utilized along with other techniques after performing simple EDA on the data.
