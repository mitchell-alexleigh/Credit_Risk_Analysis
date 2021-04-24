# Credit Risk Analysis

## Over View 
The purpose of this analysis is to compare machine learning to models. The models should determine if a person his high or low risk for a credit card. To do this, we used imbalanced-learn and scikit-learn python libraries.

## Results

### Naive Random Oversampling

* The balanced accuracy score of .62 this tells us that the overall accuracy of this algorithm on this data set is 62%
* The precision for high risk applicants is 0.01 which tells us this model had very few true positive results for high risk applicants 
* The precision for high risk applicants is 1 which tells us that this model had 100% accuracy in determining true positives for low risk applicants. 
* The recall for high risk applicants in .66 which means 66% of the high risk applicants where found to be high risk.
* The recall for low risk applicants in .58 which means 58% of the low risk applicants where found to be low risk.

### SMOTE Oversampling

* The balanced accuracy score of .66. This tells us that the overall accuracy of this algorithm on this data set is 66% which is the highest accuracy of the algorithms in this analysis.
* The precision for high risk applicants is 0.01 which tells us this model had very few true positive results for high risk applicants 
* The precision for high risk applicants is 1 which tells us that this model had 100% accuracy in determining true positives for low risk applicants. 
* The recall for high risk applicants in .63 which means 63% of the predicted high risk applicants where found to be high risk.
* The recall for low risk applicants in .69 which means 69% of the predicted low risk applicants where found to be low risk.

### Undersampling

* The balanced accuracy score of .54. This tells us that the overall accuracy of this algorithm on this data set is 54%
* The precision for high risk applicants is 0.01 which tells us this model had very few true positive results for high risk applicants 
* The precision for high risk applicants is 1 which tells us that this model had 100% accuracy in determining true positives for low risk applicants. 
* The recall for high risk applicants in .69 which means 69%  of predicted the high risk applicants where found to be high risk.
* The recall for low risk applicants in .40 which means 40% of the predicted low risk applicants where found to be low risk.

### Combination (Over and Under) Sampling

* The balanced accuracy score of .64. This tells us that the overall accuracy of this algorithm on this data set is 64%
* The precision for high risk applicants is 0.01 which tells us this model had very few true positive results for high risk applicants 
* The precision for high risk applicants is 1 which tells us that this model had 100% accuracy in determining true positives for low risk applicants. 
* The recall for high risk applicants in .72 which means 72% of the predicted high risk applicants where found to be high risk.
* The recall for low risk applicants in .57 which means 57% of the predicted low risk applicants where found to be low risk.

### Balanced Random Forest Classifier

* The balanced accuracy score of .47. This tells us that the overall accuracy of this algorithm on this data set is 47 % which is the lowest accuracy of the algorithms in this analysis.
* The precision for high risk applicants is 0.01 which tells us this model had very few true positive results for high risk applicants 
* The precision for high risk applicants is .99 which tells us that this model had 99% accuracy in determining true positives for low risk applicants. 
* The recall for high risk applicants in .85 which means 85% of the predicted high risk applicants where found to be high risk.
* The recall for low risk applicants in .09 which means 9% of the predicted low risk applicants where found to be low risk.

### Easy Ensemble AdaBoost Classifier¶

* The balanced accuracy score of .60. this tells us that the overall accuracy of this algorithm on this data set is 
* The precision for high risk applicants is 0.01 which tells us this model had very few true positive results for high risk applicants 
* The precision for high risk applicants is 1 which tells us that this model had 100% accuracy in determining true positives for low risk applicants. 
* The recall for high risk applicants in .53 which means 53% of the high risk applicants where found to be high risk.
* The recall for low risk applicants in .67 which means 67% of the low risk applicants where found to be low risk.

## Summary 

In conclusion, none of the algorithms are accurate enough to successfully differentiate a high risk applicant form a low risk applicant. The best performing algorithm, SMOTE, had a recall that determined only 69% of the predicted low risk applicants where actually found to be low risk. additionally, all algorithms had a precision of 1% for high risk applicants which means of the applicants predicted to be high risk, only 1% were actually high risk meaning an many good applicants could be rejected. 

