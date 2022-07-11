# Credit_Risk_Analysis

## Overview of the analysis:

#### Credit card credit data has been acquired from LendingClub, a peer-to-peer lending service company, to assist in evaluating which machine learning methods/algorithms offer the best predictions for credit risk. This analysis will be used to help FastLending, another peer-to-peer lending service, who would like to introduce machine learning methods to their loan application process. They believe this would be more efficient in time and accuracy to identify good candidates for loans and therefore reduce the default rates.

## Summary:
 #### In order to identify the best possible model to predict credit risk, the average F1 scores would need to be reviewed. The F1 score would be more useful then the accuracy score since there is such an uneven class distribution. For this analysis, we will focus on the F1 high risk score particularly since we want to establish the high risk candidates accurately.
In all the resampling algorithms, Cluster Centroid was the least optimal in predicting credit risk with an accuracy score of 0.54 and F1 high risk score of 0.01. So far the highest F1 score within the resampling models is the SMOTE method at 0.81, accuracy score at 0.65 and a low F1 high risk score of 0.02.
There was not much of a difference in the F1 scores and accuracy scores between the Random Over Sampling and the SMOTEEN; both models faired moderately in predicting credit risk, however looking individually at the F1 high score, both models were low in predicting the high risk applicants.

Between the two ensemble learners, both models had a good F1 score, though the accuracy score for the balanced random forest classifier was lower at 0.73.
To analyze further; when focusing on the F1 high risk score individually, the high risk is quite low but the low risk precision is at its best. This means the model wasn't optimal in predicting the high credit risk candidates. But when looking at the recall scores, both high risk and low risk scores are high. That means the model predicting both high and low risk was labeled correctly.
Thus far, none of the models are optimal to analyze high risk candidates.
