# Credit_Risk_Analysis
Module 18 Challenge

## Overview of the analysis:
The purpose of this analysis is to determine which machine learning model (MLM) scores the highest with the data provided. We will be comparing six MLMs.

## Results:
Using bulleted lists, describe

### Balanced Accuracy Scores
- Of Naive Random Oversampling: 0.648767580808264
- Of SMOTE Oversampling: 0.6159507435206336
- Of Cluster Centroids Random Undersampling: 0.590524795436141
- Of SMOTEENN Combination Sampling: 0.6419346846030192
- Of Balanced Random Forest Classifier: 0.7877672625306695
- Of Easy Ensemble AdaBoost classifier: 0.925427358175101

### Precision and Recall Scores
- Of Naive Random Oversampling (0.99, 0.69): 
![NRO](/images/nro.png)
- Of SMOTE Oversampling (0.99, 0.65): 
![SO](/images/so.png)
- Of Cluster Centroids Random Undersampling (0.99, 0.57): 
![CCRU](/images/ccru.png)
- Of SMOTEENN Combination Sampling (0.99, 0.58): 
![SCS](/images/scs.png)
- Of Balanced Random Forest Classifier (0.99, 0.91): 
![BRFC](/images/brfc.png)
- Of Easy Ensemble AdaBoost classifier (0.99, 0.94): 
![EEAC](/images/eeac.png)



## Summary:

In summary, all learning models have the same total/average precision score, but the high risk precision score is highest for the Easy Ensemble AdaBoost classifier. The recall score is also highest for the Easy Ensemble AdaBoost classifier. And the Balanced Accuracy Score is highest for the Easy Ensemble AdaBoost classifier. This MLM scores the highest in every metric analyzed. As such, this is the one we reccomend.
