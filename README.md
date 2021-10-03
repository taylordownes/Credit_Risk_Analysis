# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to use the credit card dataset from LendingClub, a peer-to-peer lending services company, to evaluate which machine learning model works best to predict credit risk. We oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm and compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Results

### Naive Random Oversampling

- Balanced Accuracy Score: 65%
- Precision Score: 99% 
- Recall Score: 60%


![image](https://user-images.githubusercontent.com/84201614/135763263-66c13ace-dad3-4d34-8213-dfb46501767d.png)



### SMOTE Oversampling

- Balanced Accuracy Score: 66%
- Precision Score: 99%
- Recall Score: 69%


![image](https://user-images.githubusercontent.com/84201614/135763335-48cee85c-db48-43af-b80b-b50b17c692fc.png)



### Undersampling

- Balanced Accuracy Score:54%
- Precision Score: 99%
- Recall Score: 40%


![image](https://user-images.githubusercontent.com/84201614/135763430-52ba8293-98c6-45e1-a043-b39c9a8ebcb4.png)



### Combination Over and Under Sampling

- Balanced Accuracy Score: 64%
- Precision Score: 99%
- Recall Score: 57%


![image](https://user-images.githubusercontent.com/84201614/135763450-d6bab5bd-a78f-47ff-9250-39956c5d4f7c.png)



### Balanced Random Forest Classifier

- Balanced Accuracy Score: 79%
- Precision Score: 99%
- Recall Score: 87%


![image](https://user-images.githubusercontent.com/84201614/135764118-89313e4c-89e7-46d4-906d-5942d5ea6f51.png)



### Easy Ensemble Classifier

- Balanced Accuracy Score:93%
- Precision Score: 99%
- Recall Score: 94%

![image](https://user-images.githubusercontent.com/84201614/135764153-853a6d20-0bbb-4267-82da-042399b5a990.png)


## Summary
Based on the results, the Easy Ensemble Classifier has the highest balanced accuracy score of 93% and appears to be the best machine learning model to predict credit risk out of the 6 models. The Easy Ensemble Classifier also has the highest recall score and F1 score and is tied with the rest at 99% for precision score. When conducting credit risk analysis, it is important to capture as many instances of high credit risk as possible, therefore, the Easy Ensemble Classifier is the best model to use when analyzing credit risk.
