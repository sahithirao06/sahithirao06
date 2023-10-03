# Machine-Learning-Project-Starter
Repository of all project documentation and Code

# State of project:
Model is completly implemented with Logistic Regression.

Important Results:

              precision    recall  f1-score   support

           0       0.99      0.99      0.99       870
           1       0.98      0.96      0.97       269

    accuracy                           0.99      1139
   macro avg       0.98      0.98      0.98      1139
weighted avg       0.99      0.99      0.99      1139


### Overview of Project
#### Introduction and goals:
In this project I worked with the email spam data of different emails to develop a machine learning model that predicts if an email is spam or not
#### Important Features:

Features here are only the text data. Relations are developed based on the words in the text which will predict if an email is spam or not

The target variable is 'spam'. This variable can have two possible outcomes: 0 or 1 where 0 refers to the case where a 0 is non-spam email and 1 is a spam email

#### Data Preprocessing:
Performed - 
1. Converting all letters to lowercase
2. Splitting the sentences to words (lemmas)
3. Splitting the to training and testing sets

##### Models used:
Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)


### Conclusion: (What I leanrt)
Results can be calculated by increasing or decreasing the features/data

When training data is decreased and testing data is increased testing accuracy is increased, accuracy started increasing

Increasing records in data can help overcome overfitting. 
