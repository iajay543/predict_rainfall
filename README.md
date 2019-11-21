# predict_rainfall
Predicting Rainfall tomorrow in Australia

This project focuses on Machine learning using pyspark. The main goal of this project is to predict rainfall tomorrow in Australia using several supervised machine learning algorithms such as Logistic Regression, Gradient Boosting, Decision Trees and Random Forest. This is basically a classification problem where the target/response/dependent variable is categorical i.e. it has 2 classes/categories (Yes/No). In order to do so, we perform various activities which are listed below:

* Importing pyspark and Initializing Spark
* Data Wrangling such as deleting not-so-important columns, detecting and imputing missing values, etc.
* Data Transformation such as converting columns which hold categorical data to numerical values for the machine learning algorithms to learn.
* Creating a feature vector and dividing the data into training and test set 
* Applying machine learning algorithms on the training set, predicting on the test set, reporting the accuracy and error on the test set
* Model evaluation using metrics such as Confusion Matrix.

The project specifications is described in 'FIT5202 Assignment 2 Specifications.pdf' file which is uploaded in this repository along with the dataset named 'weatherAUS.csv'.
