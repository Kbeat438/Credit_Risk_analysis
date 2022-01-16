# Credit_Risk_Analysis

# Overview of the analysis: 
The purpose of this analysis is to comb through 6 different sampling algorithms and decide which, if any, are best used to predict credit risk. 

# Results:

- Naive random oversampling:https://github.com/Kbeat438/Credit_Risk_analysis/blob/main/Images/Naive%20random%20oversampling.png
This algorithm produced a balanced accuracy score of 65%. The Precision for Low_risk was a perfect 100% while the precision for high_risk was 1%. The recall for high_risk and Low_risk were 62% and 68% respectfully. 

- SMOTE oversampling:https://github.com/Kbeat438/Credit_Risk_analysis/blob/main/Images/Smote%20oversampling.png
This algorithm produced a balanced accuracy score of 62%. The Precision for Low_risk was a perfect 100% while the precision for high_risk was 1%. The recall for high_risk and Low_risk were 59% and 66% respectfully. 

- Undersampling:https://github.com/Kbeat438/Credit_Risk_analysis/blob/main/Images/Undersampling.png
This algorithm produced a balanced accuracy score of 51.5%. The Precision for Low_risk was a perfect 100% while the precision for high_risk was 1%. The recall for high_risk and Low_risk were 60% and 43% respectfully. 

- Combination sampling:https://github.com/Kbeat438/Credit_Risk_analysis/blob/main/Images/Combination%20Sampling.png
This algorithm produced a balanced accuracy score of 51.5%. The Precision for Low_risk was a perfect 100% while the precision for high_risk was 1%. The recall for high_risk and Low_risk were 60% and 43% respectfully. 

- Easy Ensemble AdaBoost Classifier:https://github.com/Kbeat438/Credit_Risk_analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png
This algorithm produced a balanced accuracy score of 92.5%. The Precision for Low_risk was a perfect 100% while the precision for high_risk was 7%. The recall for high_risk and Low_risk were 91% and 94 % respectfully. 

- Balanced Random forest classifier:https://github.com/Kbeat438/Credit_Risk_analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.png
This algorithm produced a balanced accuracy score of 78%. The Precision for Low_risk was a perfect 100% while the precision for high_risk was 4%. The recall for high_risk and Low_risk were 67% and 91% respectfully. 


# Summary: From the results of these sampling algorithms we see that most of the algorithms have a accuracy rate below 80%. There is only one that is above, and that is Easy Ensemble AdaBoost Ckassifier with an accuracy score of 92.5%. The precision for all of these algorithms is relatively the same. Each module is perfect with low_risk and bad at high_risk, which is disappointing since we would be more interested to know if a person is a high_risk canidate than a low risk. The Recall for most cases was also below 80%, besides Easy Ensemble AdaBoost Classifier again, with a score of 91% on low_risk and 94% on high_risk. It becomes clear from the data then that the Easy Ensemble AdaBoost Classifier is the best choice. It may have low precision just like the rest but recall is more important in this instance so that the system can flag if a client is high_risk and we can do our due diligence before we decide to give the client a loan or not. 