# product-performance-analysis
Research question
In an increasingly competitive e-commerce environment, how can product performance be analysed and modelled in order to better understand and anticipate consumer purchasing behaviour?

General objective
To analyse and model product performance in an e-commerce context

Specific objectives
To develop and compare various machine learning models for predicting sales performance
To identify the factors that have the greatest influence on customer satisfaction

A synthetic yet realistic dataset from Kaggle, simulating an e-commerce environment
This dataset comprises 2,000 records and 9 variables
(product price, discount rate, average customer rating, number of reviews, stock availability, delivery time, return rate, category ID)

Pre-processing and exploratory analysis
Imputation of missing values: median for quantitative variables, mode for the qualitative variable (stock availability)
Identification of outliers and standardisation of quantitative variables.
Split the dataset into 80% training and 20% test.

Defining an item’s performance: intuitive analysis, implementation of unsupervised algorithms (K-means, DBSCAN and TSNE) to cluster items into homogeneous classes

Predicting sales performance and identifying the factors with the greatest influence on customer satisfaction: implementation of KNN, Naive Bayes, SVM, decision tree, neural network and random forest algorithms 
