# Credit_Risk_Analysis

# Overview of Analysis
The purpose of this analysis is to determine which machine learning model is the best at predicting the credit risk of applicants for loans.  Classifying applicants into risky and not risky is an imbalanced classification as one outnumbers the other.  For the purposes of this analysis however being able to predict which model best determines a good loan from a bad loan is important to determine who should be given a line of credit.

## Results

1. The balanced accuracy scores for the six models are as follows: NRO - 0.66, Smote - 0.62, CC - 0.53, SMOTEENN - 0.66, BRFC - 0.78, EEC - 0.93.

2. The precision scores for all six models was the same as dertermined by the imbalanced classification report.  The recall scores are as follows: NRO - 0.67, Smote - 0.64, CC - 0.45, SMOTEENN - 0.57, BRFC - 0.87, EEC - 0.94.



## Summary
According to the results the ecc and BRFC models were by far the most accurate and had the highest recall scores of all six learning models.  For the given data which is loan applicants being high-risk or low-risk these two models wwould be the ones to choose.  As for a specific recommendation, I would recommend the ECC model due to how accurate it is and also how well it was able to recall from the training and testing data.
