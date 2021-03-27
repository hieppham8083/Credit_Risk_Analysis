# Credit_Risk_Analysis
- The purpose of this analysis was to apply machine learning to solve and predict credit risk. Refer to [credit_risk_resampling.ipynb](../main/credit_risk_resampling.ipynb) and [credit_risk_ensemble.ipynb](../main/credit_risk_ensemble.ipynb)

## Challenge
- Use Resampling Models to Predict Credit Risk (Deliverble1): 
  - Naive Random Oversampling results: accuracy is 64%, precision of high_risk is 1%,  and the recall is 73%
    ![alt text](../main/RandomOversampling_Deliverble1.png) 
  - Naive Random Oversampling results: accuracy is 66%, precision of high_risk is 1%,  and the recall is 63%
    ![alt text](../main/SMOTEOversampling_Deliverble1.png) 
- Use the SMOTEENN algorithm to Predict Credit Risk (Deliverble2):
  - Undersampling results: accuracy is 52%, precision of high_risk is 1%,  and the recall is 69%
    ![alt text](../main/Undersampling_Deliverble2.png) 
  - Combination results: accuracy is 64%, precision of high_risk is 1%,  and the recall is 72%
  - ![alt text](../main/Combination_Deliverble2.png) 
- Use Ensemble Classifiers to Predict Credit Risk (Deliverble3):
   - Balanced Random Forest Classifier results: accuracy is 78%, precision of high_risk is 3%,  and the recall is 69%
    ![alt text](../main/BalancedRandomForest_Deliverble3.png) 
   - Easy Ensemble AdaBoost Classifier results: accuracy is 93%, precision of high_risk is 9%,  and the recall is 92%
    ![alt text](../main/EasyEnsembleAdaBoost_Deliverble3.png) 

## Summary
- Recommendation: Base on the results, We should use Easy Ensemble AdaBoost Classifier because it had high accuracy and good balance of precision and recall.
- I would not recommend to use the first four models to predict credit risk.
