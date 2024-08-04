# Credit_Card_Fraud_Detection
# Logistic Regression Model for Classification
This project involves predicting credit card fraud using a Logistic Regression model. The dataset contains various features related to credit card transactions, and the goal is to accurately identify fraudulent transactions.
# Project Overview:
# 1- Loading the Dataset:
The dataset is loaded using the pandas library. This step involves reading the dataset file into a DataFrame, allowing for easy manipulation and analysis.
# 2- Exploring and Describing the Data by head, tail, describe, shape and info.
# 3- Handling Imbalanced Data:
The dataset is highly imbalanced, with a majority of transactions being legitimate and only a small fraction being fraudulent. To address this, a sample dataset is created to have a similar distribution of fraudulent and legitimate transactions. This can be done through techniques such as under-sampling the majority class or over-sampling the minority class.
# 4- Splitting the Data:
The dataset is divided into training and testing sets using the train_test_split function. This step is crucial for evaluating the performance of the model on unseen data.
# 5- Building and Training the Model:
A Logistic Regression model is built and trained on the training set. Logistic Regression is a statistical method for binary classification, making it suitable for distinguishing between fraudulent and legitimate transactions.
# 6- Model Evaluation:
The performance of the model is evaluated using various metrics such as accuracy, precision, recall, and the F1-score. These metrics help in understanding how well the model is performing in predicting fraudulent transactions.
