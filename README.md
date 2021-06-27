# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to create supervised machine learning models that would help to predict credit risk. To do this, imbalanced-learn and scikit-learn libraries were used to build and evaluate models using resampling. Specifically, oversampling was conducted using RandomOverSampler and SMOTE algorithms, undersampling using the ClusterCentroids algorithm and a combination approach using the SMOTEENN algorithm. Finally, two new machine learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier, were leveraged to predict credit risk.

## Results
### RandomOverSampler
- The balanced accuracy score for this model was 0.647, indicating that it was correctly able to predict loan risk 64.7% of the time

![ros_balanced_accuracy.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/ros_balanced_accuracy.png)

-
-

![ros_classification_report.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/ros_classification_report.png)

### SMOTE
- The balanced accuracy score for this model was 0.662, indicating that it was correctly able to predict loan risk 66.2% of the time

![smote_balanced_accuracy.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/smote_balanced_accuracy.png)

-
-

![smote_classification_report.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/smote_classification_report.png)

### ClusterCentroids
- The balanced accuracy score for this model was 0.545, indicating that it was correctly able to predict loan risk 54.5% of the time

![cc_balanced_accuracy.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/cc_balanced_accuracy.png)

-
-

![cc_classification_report.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/cc_classification_report.png)

### SMOTEEN
- The balanced accuracy score for this model was 0.647, indicating that it was correctly able to predict loan risk 67.8% of the time

![smoteen_balanced_accuracy.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/smoteen_balanced_accuracy.png)

-
-

![smoteen_classification_report.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/smoteen_classification_report.png)

### BalancedRandomForestClassifier
- The balanced accuracy score for this model was 0.789, indicating that it was correctly able to predict loan risk 78.9% of the time

![brfc_balanced_accuracy.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/brfc_balanced_accuracy.png)

-
-

![brfc_classification_report.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/brfc_classification_report.png)

### EasyEnsembleClassifier
- The balanced accuracy score for this model was 0.932, indicating that it was correctly able to predict loan risk 93.2% of the time

![eec_balanced_accuracy.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/eec_balanced_accuracy.png)

-
-

![eec_classification_report.png](https://github.com/vanessamignelli/Credit_Risk_Analysis/blob/main/resources/eec_classification_report.png)

## Summary
