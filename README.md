# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to compare the accuracy of multiple machine learning models. All used logistic regression in combination with sampling techniques.

## Results
- Naive Random Oversampling: accuracy = 64.9%, precision = 0.99, recall = 0.57
- SMOTE Oversampling: accuracy = 65.8%, precision = 0.99, recall = 0.68
- Clustered Centroids Undersampling: accuracy = 54.4%, precision = 0.99, recall = 0.40
- SMOTEENN Combination Sampling: accuracy = 64.8%, precision = 0.99, recall = 0.58

## Summary
SMOTE Oversampling seemed to perform the best out of the 4 considered, and the Undersamping and SMOTEENN methods performed worse on this dataset than the basic Random Oversampling. I would recommend none of the above methods, as an average accuracy of 65.8% is unnacceptable for any production use. If you had to use one, I would recommend SMOTE Oversampling because it was the most accurate and robust (had an f1 score of 0.81, significantly higher than the other methods). 
