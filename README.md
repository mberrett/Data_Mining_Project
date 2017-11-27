# Data_Mining_Project

by Matias Berretta, Vaibhav Dixit, Rohini Mandge

Project Outline

Test Ensemble Classifier consisiting of five other classifiers: Random Forest, K-Nearest Neighbors, Logistic Regression, SVM, Naive Bayes. 

For each data set, test Ensemble Classifier with and without bagging (sklearn library) to address unbalanced nature of the data. 

1. Section 1: Preliminary Test

    a) Drop All Missing Values
    b) Test Ensemble Classifier with default settings 
    c) Test with and without bagging 

2. Section 2: Imputation

    Repeat 1.b) and 1.c) with the data sets produced by the following imputation approaches 
    
    a) Mode Imputation: Fill missing values with most frequent value

    b) RandomForest Imputation: Fill missing values with RandomForest prediction

    c) KNN Imputation: Fill missing values with KNN prediction

3. Section 3: Optimization

    a) Find the best parameters for each algorithm in the ensemble classifier 
  
