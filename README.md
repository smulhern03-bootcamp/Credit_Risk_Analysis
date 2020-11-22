# Credit_Risk_Analysis
## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, this analysis will perform various machine learning proceedures.  These proceedures will attempt to determine low and high risk loans. Proceedures used will be RandomOverSampler and SMOTE algorithms, and undersampling using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, a comparison of two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier will be used

## Results: 
### Oversampling
Naive Random Oversampling
![Random](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.PNG)

SMOTE Oversampling
![SMOTE](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.PNG)

Of the two oversampling alogrithms, Naive Random Oversampling produced the higher true positives but also higher false positives.  Of the two oversampling models, SMOTE with its higher accuracy of true vs false positives is the better model.

### Undersampling
ClusterCentroid

![Undersampling](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)

Undersampling produced the highest false positives so should not be considered.


### Combination (Over and Under)
SMOTEENN
![combination](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Combination.PNG)
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results. There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

### Ensemble
Balanced Random Forest Classifiers
![balanced forest](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest.PNG)

Easy Ensemble AdaBoost Classifiers
![easy ensemble](https://github.com/smulhern03-bootcamp/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost.PNG)

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning. There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
