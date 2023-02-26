# Online Payments Fraud Detection

![proj3](https://user-images.githubusercontent.com/86102231/221410144-2c07a913-f8d8-4a2f-829d-22749bfce53e.png)

## Author [Gaurab Kundu](https://www.linkedin.com/in/gaurab-kundu/)

## Project Overview

The introduction of online payment systems has helped a lot in the ease of payments. But, at the same time, it increased in payment frauds. Online payment frauds can happen with anyone using any payment system, especially while making payments using a credit card. That is why detecting online payment fraud is very important for credit card companies to ensure that the customers are not getting charged for the products and services they never paid. In this project, I will build a machine learning model using python to detect online payments fraud.

## Tools & Technologies Used

Programming Language: Python

Libraries: Pandas, Numpy, Matplotlib, Scikit-Learn.

Jupyter Notebbook

## Online Payments Fraud Detection with Machine Learning

To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud.

## The DataSet

For this project, I collected a [dataset](https://www.kaggle.com/ealaxi/paysim1/download) from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. 

Below are all the columns from the dataset I’m using here:

1. step: represents a unit of time where 1 step equals 1 hour
2. type: type of online transaction
3. amount: the amount of the transaction
4. nameOrig: customer starting the transaction
5. oldbalanceOrg: balance before the transaction
6. newbalanceOrig: balance after the transaction
7. nameDest: recipient of the transaction
8. oldbalanceDest: initial balance of recipient before the transaction
9. newbalanceDest: the new balance of recipient after the transaction
10. isFraud: fraud transaction

