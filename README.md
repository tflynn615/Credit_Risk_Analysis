# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this analysis is to use a credit card credit dataset from LendingClub, a peer-to-peer lending services company, to determine which factors make a credit card application high or low risk for a lender. 

## Results: 

I will list the accuracy results of each model below with screenshots from the data. 

### - Random Over Sampling:

![ROS_Scores.png](Pictures/ROS_Scores.png)

### - SMOTE Over Sampling:

![SMOTE_Scores.png](Pictures/SMOTE_Scores.png)

### - Cluster Centroids Over Sampling: 

![Cluster_Scores.png](Pictures/Cluster_Scores.png)

### - SMOTEENN:

![SMOTEENN_Scores.png](Pictures/SMOTEENN_Scores.png)

### - Balanced Random Forest Classifier:

![RF_scores.png](Pictures/RF_scores.png)

### - Easy Ensemble Adaboost Classifier:

![ee_scores.png](Pictures/ee_scores.png)



## Summary: 

In summary, the accuracy scores for five of the the six supervised machine learning methods used range between 51% and 67% with the exception of the Easy Ensemble mehtod which is about 91% accurate. For this reason, I recommend the Easy Ensemble method to identify loans for auto acception because you want to minimize the risk that you accept as a lender. This model will most accurately identify applications that closely align with this model saving loan agents' time to review those applications which do not closely align with the identified influencing factors.  
