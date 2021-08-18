# Credit_Risk_Analysis
## Overview:
We wanted to analyze all the factors from the loan_stats csv to help us predict whether someone is a high or low risk status for a credit card. We used imbalanced-learn and scikit-learn libraries to create our models and used resampling to evaluate.

## Results:
* Naive Random Oversampling results: accuracy score is 64.8% with a precision of 99% and recall of 60% 
![alt text](https://github.com/amarks5/Credit_Risk_Analysis/blob/main/images/naive.PNG)


* SMOTE oversampling results: accuracy score is 66.3% with a precision of 99% and recall of 69%
![alt text](https://github.com/amarks5/Credit_Risk_Analysis/blob/main/images/smote.PNG)


* Undersampling results: accuracy score is 66.3% with a precision of 99% and recall of 40%
![alt text](https://github.com/amarks5/Credit_Risk_Analysis/blob/main/images/undersampling.PNG)


* Combination results: accuracy score is 54.4% with a precision of 99% and recall of 58%
![alt text](https://github.com/amarks5/Credit_Risk_Analysis/blob/main/images/combination.PNG)


* Balanced Random Forest Classifier results: accuracy score is 77.8% with a precision of 99% and recall of 87%
![alt text](https://github.com/amarks5/Credit_Risk_Analysis/blob/main/images/balanced_random_forest_classifier.PNG)


* Easy Ensemble results: accuracy score is 93.2% with a precision of 99% and recall of 94%
![alt text](https://github.com/amarks5/Credit_Risk_Analysis/blob/main/images/easy_ensemble.PNG)

## Summary:
The first four models we ran were low in accuracy and were not balanced when it came to precision and recall scores (ideally you want precision and recall to be pretty balanced). The ensemble classifiers definitely had the higher accuracy. It appears the Easy Ensemble had the best balance of all the models with a high accuracy score, precision and recall scores. I recommend using the ensemble classifiers.

