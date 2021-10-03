# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to ue the credit card dataset from LendingClub, a peer-to-peer lending services company, to evaluate which machine learning model works best to predict credit risk. We oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorith and compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

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

- Balanced Accuracy Score:64%
- Precision Score: 99%
- Recall Score: 57%


![image](https://user-images.githubusercontent.com/84201614/135763450-d6bab5bd-a78f-47ff-9250-39956c5d4f7c.png)



### Balanced Random Forest Classifier

- Balanced Accuracy Score:68%
- Precision Score: 100%
- Recall Score: 100%


![image](https://user-images.githubusercontent.com/84201614/135763485-91c6ac04-7ff1-44eb-8f79-e143a8d5a704.png)



### Easy Ensemble Classifier

- Balanced Accuracy Score:93%
- Precision Score: 99%
- Recall Score: 94%


![image](https://user-images.githubusercontent.com/84201614/135763565-2ae91eee-6d92-48e1-9f0b-5c284f1333a9.png)


## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
