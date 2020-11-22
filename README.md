# Credit_Risk_Analysis
## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, this analysis will perform various machine learning proceedures.  These proceedures will attempt to determine low and high risk loans. Proceedures used will be RandomOverSampler and SMOTE algorithms, and undersampling using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, a comparison of two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier will be used

## Results: 
### Oversampling
Naive Random Oversampling
![Random](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.PNG)
![Random stats](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling_stats.PNG)

SMOTE Oversampling
![SMOTE](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.PNG)
![SMOTE stats](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling_stats.PNG)

### Undersampling
![Undersampling](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)
![Undersampling stats](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Undersampling_stats.PNG)

### Combination (Over and Under)
![combination](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Combination.PNG)
![combination stats](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Combination_stats.PNG)

### Ensemble
Balanced Random Forest Classifiers
![balanced forest](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest.PNG)
![balanced forest stats](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest_stats.PNG)

Easy Ensemble AdaBoost Classifiers
![easy ensemble](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost.PNG)
![easy ensemble stats](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost_stats.PNG)

* The SMOTEENN alogrithm performed the worst with an F1 score of .58.  The Easy Ensemble performed the best with an F1 score of .97
* All algorithms has high presicion scores
* Sensitivity is where the algorithms differed.  Only the ensemble algorithms have above .70 sensitivity scores.

## Summary: 
Easy Ensemble AdaBoost performed the best out of all the algorithms.  Going forward, the company should use the Easy Ensemble AdaBoost alogrithm for predictions on data.  Each score of significance was above .95.  The algorithm was head-and-shoulders above any other.
