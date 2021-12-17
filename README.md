# Credit Risk Analysis

## Overview
##### In this project, we built and evaluated machine learning models to predict credit risk. We ran the data through many different models to determine the best model to predict credit risk. This was all done in Python in Jupyter Notebooks.  

## Results 

### Random Oversampling 

![Alt Image Text](https://github.com/mkback/Credit_Risk_Analysis/blob/main/Images/Random_Oversampling.jpg)

##### - The balanced accuracy is 64.56%
##### - The high risk precision score is only 1% and the recall is 61%
##### - The low risk population is much larger with a precsion score of 100% and a recall score of 68%

### Smote Oversampling 
![Alt Image Text](https://github.com/mkback/Credit_Risk_Analysis/blob/main/Images/Smote.png)
##### - The balanced accuracy is 62.34%
##### - The high risk precision score is only 1% and the recall is 61%
##### - The low risk has precsion score of 100% and a recall score of 64%

### Undersampling 
![Alt Image Text](https://github.com/mkback/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)
##### - The balanced accuracy is 63.96%
##### - The high risk precision score is only 1% and the recall is 57%
##### - The low risk has precsion score of 100% and a recall score of 45%

### Combination Sampling
![Alt Image Text](https://github.com/mkback/Credit_Risk_Analysis/blob/main/Images/Combo.png)
##### - The balanced accuracy is 63.96%
##### - The high risk precision score is 1% and the recall is 70%
##### - The low risk has precsion score of 100% and a recall score of 58%

### Balanced Random Forest Classifier
![Alt Image Text](https://github.com/mkback/Credit_Risk_Analysis/blob/main/Images/BRFC.png)
##### - The balanced accuracy is 78.78%
##### - The high risk precision score is 4% and the recall is 67%
##### - The low risk has precsion score of 100% and a recall score of 91%

### Easy Ensemble AdaBoost Classifier
![Alt Image Text](https://github.com/mkback/Credit_Risk_Analysis/blob/main/Images/EEC.png)
##### - The balanced accuracy is 92.54%
##### - The high risk precision score is 7% and the recall is 91%
##### - The low risk has precsion score of 100% and a recall score of 94%




## Summary 

##### Most of these models do not predict high credit risk well at all. All have less than 10% precision and most have less than 70% sensitivity. This in turn yielded very low F1 scores, further showing weak results. However, both the Balanced Random Forest Classifier and Easy Ensemble Adaboost Classifier had high precision and sensitivity scores for predicting low risk credit. I would recommend the bank use the Easy Ensemble Adaboost Classifier to predict low credit risk because it had a precision of 100%, sensitivity of 94% and an F1 score of 97%. This model also had a balanced accuracy of 92% which is the highest we have seen as well. 
