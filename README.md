# Credit_Risk_Analysis

## Overview
Using supervised machine learning I will create a model to predict credit risk. In this analysis oversampling, undersampling, combined, and ensemble models will be created and compared. Data for this analysis comes from LendingClub.

## Results
### Oversampling

![naive random oversampling](https://user-images.githubusercontent.com/57120024/175618406-fc728a7c-adae-4149-9481-c528d96205f0.png)

![SMOTE](https://user-images.githubusercontent.com/57120024/175618414-3f98d5ce-9946-44d2-b298-5a3dde4bd7cb.png)

### Undersampling

![ClusterCentroid](https://user-images.githubusercontent.com/57120024/175618435-a803e112-1a99-4ab3-9345-a96cc5b7569e.png)

### Combination 

![SMOTEENN](https://user-images.githubusercontent.com/57120024/175618463-f6ebc9e4-9b92-4ba7-be17-af4ce1f4a1f9.png)


### Ensemble Classifiers

![BalancedRandom ForestCalssifier](https://user-images.githubusercontent.com/57120024/175618478-654244d7-1861-46cd-a88d-a90a6971f0d6.png)

![EasyEnsemble ada](https://user-images.githubusercontent.com/57120024/175618492-3c23edfe-7bd8-4f80-9ac2-371026b80acb.png)


## Summary

When looking at the results of each model it is clear the EasyEnsembleClassifier was most effective in predicting credit risk. EasyEnsemble provides the highest recall score which is important in credit-risk because false negatives could results in issuing a loan to a consumer who will not be able to pay it back. Precision for credit risk is not as important because we would rather flag all potential high risk applicants. 

