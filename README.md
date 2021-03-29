# Credit_Risk_Analysis
Author: Jerome Simmons

## Overview of the Analysis
Using credit card data from LendingClub, I have applied different sampling techniques to build predictive models that assesses credit risk. I have oversampled the data using the RandomOverSampler and SMOTE algorithms and undersampled the data using ClusterCentroids algorithm. I took a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Upon assessing results from these four methods, I applied a Balanced Random Forest Classifier and an Easy Ensemble Classifier ot predict credit risk. In the sections below, I walkthrough the results of all six approaches by assessing the balanced accuracy score, the precision, and the recall scores.

## Results
Using bulleted lists, describe the balanced accuracy score and the precision and the recall scores of all six machine learning models.

#### Naive Random Oversampling Results
The Naive Random Oversampling approach generated a balanced accuracy score of 63.8%. The model precision for was very low for the high risk category (0.1) and very high for the low risk category (1.0). This means that the
![Images/CRR_M1_Random_Oversampling.png](Images/CRR_M1_Random_Oversampling.png)

#### SMOTE Oversampling Results
![Images/CRR_M2_SMOTE_OverSampling.png](Images/CRR_M2_SMOTE_OverSampling.png)

#### Undersampling Results
![Images/CRR_M3_UnderSampling.png](Images/CRR_M3_UnderSampling.png)

#### Combination SMOTEEN over & undersampling Results
![Images/CRR_M4_SMOTEEN.png](Images/CRR_M4_SMOTEEN.png)

#### Balanced Random Forest Classifier Results
![Images/CRR_M5_BALANCED_RFC.png](Images/CRR_M5_BALANCED_RFC.png)

![Images/CRR_M5_BALANCED_RFC_FEAT_IMPORTANCE.png](Images/CRR_M5_BALANCED_RFC_FEAT_IMPORTANCE.png)

#### Easy Ensemble AdaBoost Classifier Results
![Images/CRR_M6_EEC.png](Images/CRR_M6_EEC.png)



## Summary
Summarize the results of the ML models and include a recommendaiton on the model to use, if any. If not, justify your reasoning.
