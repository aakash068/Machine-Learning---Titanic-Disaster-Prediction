# Machine-Learning---Titanic-Disaster-Prediction

Solution:- 

Contents
Table of Content
1. Data Definations
2. Exploratory Data Analysis
3. Contigency Table Analysis: Chi-Square test for Independence
4. Missing Values
5. Feature Encoding
6. Model Fitting
7. Classification Performance Analysis
8. K-Fold Crossvalidation
9. Confidence Intervals of the coefficients in Logistic Regression
10. Prediction on entire dataset
11. Preparing Test Dataset for prediction submission
12. Logistic Regression from scratch using numpy & pandas

Key Highlights:
Chance for Surviving (24%) is worst in 3rd-Passenger Class
Majority of Female travelled in 1st-Class and Majority of Male travelled in 3rd-Class
Majority of Passengers travelling in Pclass-3 had 0 Fare & didnot survive, meaning, a lot of crew(sailors, cabin crew, workers,...) travelled in 3rd-Class. Some Male Passengers travelling in 1st Class had 0 Fare and didnot Survive, which means they were Captains, High ranking officers. Infact, all persons with 0 Fare were Male, and travelled to Port City-'Southampton'(hence, can be assumed the last Destination of the Ship)
Almost all Female travelling in Pclass-1 & 2nd Class had survived.
Almost all Male travelling in Pclass-2 & 3 didnot survive
Most of Male Victims had initials - 'Mr'
1. Chi-Square test for independence to check relation between Nominal Variables
2. Logistic Regression implemented from scratch
3. Model Performance:
Overall Accuracy : 0.79
Recall: TP/(TP+FN) is := 0.71
Precision : TP/(TP+FP) is := 0.74
F1 Score : 2/(1/recall + 1/precision) is := 0.72
AUC Score := 0.75
