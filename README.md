# Risky_Business

In this assignment you will build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

## Resampling

Which model had the best balanced accuracy score?
*SMOTE - Oversampling had the best balanced accuracy score*



Which model had the best recall score?
*Tied beteween Logistic regression and SMOTEEN*



Which model had the best geometric mean score?
*The geometric mean score of all models are the same*




## Ensemble Learning

Which model had the best balanced accuracy score?
*The model with the best score is EasyEnsembleClassifier*


Which model had the best recall score?
*The Easy Ensemble Classifier model had the best recall score marginally double checked by looking at the confusion matirx*

Which model had the best geometric mean score?
*The geometric mean of both models are the same*

What are the top three features?
*The top three features are total payment (total_pymnt), total reconciled principal (total_rec_prncp), and last payment amount (last_pymnt_amnt) which will end up having more of an impact on the loan status*