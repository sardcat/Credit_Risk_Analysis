# Credit Risk Analysis

## Overview
Resampling data with `imbalanced-learn` and `scikit-learn` libraries to build, evaluate and compare four Logistic Regression models `RandomOverSampler`, `SMOTE`, `ClusterCentroids` and `SMOTEENN` with two Ensemble Learners `BalancedRandomForestClassifier` and `EasyEnsembleClassifier` that predict credit risk.

## Results

Figure 1.) Oversampling with `RandomOverSampler`.

![](Resources/Fig1.png)

* Oversampling using `RandomOverSampler`: high risk accuracy of 1%, precision 59%; low risk accuracy of 100%, precision 68%.



Figure 2.) Oversampling with `SMOTE`.

![](Resources/Fig2.png)

* Oversampling using `SMOTE`: high risk accuracy of 1%, precision 60%; low risk accuracy of 100%, precision 66%.



Figure 3.) Undersampling with `ClusterCentroids`.

![](Resources/Fig3.png)

* Oversampling using `ClusterCentroids`: high risk accuracy of 1%, precision 61%; low risk accuracy of 100%, precision 45%.



Figure 4.) Undersampling with `SMOTEENN`.

![](Resources/Fig4.png)

* Oversampling using `SMOTEENN`: high risk accuracy of 1%, precision 72%; low risk accuracy of 100%, precision 58%.



Figure 5.) Ensemble Learner with `BalancedRandomForestClassifier`.

![](Resources/Fig5.png)

* Ensemble Learner using `BalancedRandomForestClassifier`: high risk accuracy of 4%, precision 67%; low risk accuracy of 100%, precision 91%.



Figure 6.) Ensemble Learner with `EasyEnsembleClassifier`.

![](Resources/Fig6.png)

* Ensemble Learner using `EasyEnsembleClassifier`: high risk accuracy of 7%, precision 91%; low risk accuracy of 100%, precision 94%.


## Summary
All the models produced an accuracy of 100% for Low Risk identification. With High Risk being the focus for identifying credit risk, the utilization of both Oversampling and Undersampling modfels never yielded an accuracy over 1% or a precision above 75%. Both Ensemble Learners resulted in accuracy for High Risk over 1%, with `EasyEnsembleClassifier` giving the best results with 7% accuracy and 91% precision. Going forward, `EasyEnsembleClassifier` would be recommended in this scenario.
