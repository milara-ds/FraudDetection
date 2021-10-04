# FraudDetection
This repository stores the files of a Machine Learning project using transactions made by credit cards in September 2013 by European cardholders.

Introduction:
    -Machine Learning models are very useful for businesses in many industries. Nevertheless, to make a model be valuable for a company it must be presentend in terms that anyone in the company can easly understand. Rather than presenting a model in terms of a metric (Accuracy, F1, ROC-AUC) it is better to present it in terms of monetary costs and/or benefits. Unfortunately, many books focus only on the model metrics and not in the business metrics, however there a few books and sites providing relevant model-business techniques. This kernel shows an approach of how to deal with this problem.
    -Furthermore, in real world scenarios a vast mayority of problems have to deal with imbalanced datasets as well. An imbalanced datset is when the amount of instances of the target variable, in this case the frauds, has higher number of the negative than the positive class. Many of the examples in the books are focused on how to train a model with balanced datasets and only mention some ideas to deal with imbalanced datasets, thus it is necessary to dig more to find how to deal with this problem. This kernel show some of the techiques to tackle this kind of issues.
    -Link to the dataset used: https://www.kaggle.com/mlg-ulb/creditcardfraud
    -This notebook is based on the notebook of Robin Teuwens with additions such as feature selection, hyperparameters tunning, learning and scalability curves and Cost/Profit curves.

Objectives:
    -To find the model that generates the lowest cost to detect frauds
    -To show how to deal with imbalanced datasets
