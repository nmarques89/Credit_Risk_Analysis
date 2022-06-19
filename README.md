# Credit_Risk_Analysis
## Overview
This project built and evaluated multiple machine learning models to forecast potential credit risk.
The project proceeded according to the following steps:

-oversample the data using the RandomOverSampler and SMOTE algorithms.
-Undersample the data using the ClusterCentroids algorithm.
-Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
-Comparisson of both learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.
Following an evaluation of the model performance a recommendation will be made regarding whether or not they should be used to predict credit risk.

## Results
 **Random Over Sample**
 
 The balanced accuracy score is 65%.
 
 **SMOTE MODEL**
 
 Similar results at 64%
 
 **Cluster Centroids**
 
 Decrease in Balanced Accuracy to 52%
 
 **SMOTEEN Model**
 
 62% balanced accuracy, within range of both Random Over Sample and SMOTE Models
 
 **BalancedRandomForestClassifier Model**
 
 **EasyEnsembleClassifier Model**
 
 ## Summary
