# Credit Risk Analysis

## Overview
Resampling data with `imbalanced-learn` and `scikit-learn` libraries to build, evaluate and compare four Logistic Regression models `RandomOverSampler`, `SMOTE` `ClusterCentroids` and `SMOTEENN` with two Ensemble Learners `BalancedRandomForestClassifier` and `EasyEnsembleClassifier` that predict credit risk.

## Results

Figure 1.) Oversampling with `RandomOverSampler`

![](Resources/Fig1.png)

* Oversampling using `RandomOverSampler`: high risk accuracy of 1%, precision 59%; low risk accuracy of 100%, precision 68%.

![](Resources/Fig2.png)

* Oversampling using `SMOTE`: high risk accuracy of 1%, precision 59%; low risk accuracy of 100%, precision 68%.
