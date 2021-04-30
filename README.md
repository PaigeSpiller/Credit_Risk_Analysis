# Credit_Risk_Analysis

## Purpose:
#### To perform a loan prediction risk analysis for customers seeking loans using six different types of machine learning models.  Additionally the six different models will be assesed for which is best suited to be used for the risk analysis.   

## Results:

#### The following charts show the balanced accuracy score for each of the six models as well as the precision and recall scores.  

#### ![BAS.PNG](Resources/BAS.PNG)
#### ----------------------------------------------------------------------------------------------
#### Naive Random Oversampling
#### ![randOS.PNG](Resources/randOS.PNG) 
#### * high risk precision:
#### * high risk recall:
#### * low risk precision:
#### * low risk recall:
#### ----------------------------------------------------------------------------------------------
#### SMOTE Oversampling
#### ![SMOTE.PNG](Resources/SMOTE.PNG)  
#### * high risk precision: 1%
#### * high risk recall: 67%
#### * low risk precision: 100%
#### * low risk recall: 63%
#### ----------------------------------------------------------------------------------------------
#### Undersampling
#### ![UnderS.PNG](Resources/UnderS.PNG)
#### * high risk precision: 1%
#### * high risk recall: 61%
#### * low risk precision: 100%
#### * low risk recall: 45%
#### ----------------------------------------------------------------------------------------------
#### Combination (Over and Under) Sampling
#### ![Combo.PNG](Resources/Combo.PNG)
#### * high risk precision: 1%
#### * high risk recall: 70%
#### * low risk precision: 100%
#### * low risk recall: 57%
#### ----------------------------------------------------------------------------------------------
#### Balanced Random Forest Classifier
#### ![BRF.PNG](Resources/BRF.PNG)
#### * high risk precision: 1%
#### * high risk recall: 59%
#### * low risk precision: 100%
#### * low risk recall: 68%
#### ----------------------------------------------------------------------------------------------
#### Easy Ensemble AdaBoost Classifier
#### ![EasyE.PNG](Resources/EasyE.PNG)
#### * high risk precision: 7%
#### * high risk recall: 91%
#### * low risk precision: 100%
#### * low risk recall: 94%

## Summary:
#### The ability for a model to predict the high risk customers is the most important factor when assesing performancere of the models.  
#### Based on these factors, the best perfoming model was the easy ensemble AdaBoost classifier.  This model is the recommended model to use for determining high risk and low risk customers. 
