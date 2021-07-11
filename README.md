# Credit_Risk_Analysis
## Overview
In this project, we are asked to predict credit risk. We predict it by using Python to build machine learning models. We evaulate the data using the following models.
- Using SMOTE and RandomOverSampler to oversample the data.
- Using ClusterCentroids to undersample the data. 
- Using SMOTEENN to combine the oversample and undersample data. 
- Using BalancedRandomForestClassifier and EasyEnsembleClassifier, which reduce bias, and compare the two machine learning models. 

## Results
RandomOverSampler Model
- This model's accuracy test is 65%. 
- Precision high risk is at 1%.
- Precision low risk is at 100%.
- Recall high risk is at 69%.
- Recall low risk is at 60%.

![oversampling](https://user-images.githubusercontent.com/80054925/125202478-675b9300-e239-11eb-9239-860c096a93de.png)

SMOTE Oversample
- This model's accuracy test is 66%.
- Precision high risk is at 1%.
- Precision high risk is at 100%.
- Recall high risk is at 63%.
- Recall low risk is at 69%. 

![smote_sampling](https://user-images.githubusercontent.com/80054925/125202749-9fafa100-e23a-11eb-8d8e-8722ad8c67d0.png)

Cluster Centroid Undersampling
- This model's accuracy test is 66%
- Precision high risk is at 1%
- Precision low risk is at 100%. 
- Recall high risk is at 69%.
- Recall low risk is at 40%.

![undersampling](https://user-images.githubusercontent.com/80054925/125202967-cc17ed00-e23b-11eb-8480-2b78ad340ec6.png)


SMOTEENN Combination
- This model's accuracy test is 54%.
- Precision high risk is at 1%.
- Precision low risk is at 100%.
- Recall high risk is at 72%.
- Recall low risk is at 57%.

![combined_sampling](https://user-images.githubusercontent.com/80054925/125202945-ae4a8800-e23b-11eb-9144-55a5fafacf8c.png)

BalancedRandomForest
- This model's accuracy test is 77%.
- Precision high risk is at 3%.
- Precision low risk is at 100%.
- Recall high risk is at 65%.
- Recall low risk is at 88%.

![balanced_classifier](https://user-images.githubusercontent.com/80054925/125203054-53fdf700-e23c-11eb-80ab-7ecc83c58e0d.png)

Easy Ensemble AdaBoost Classifier
- This model's accuracy test is 92%.
- Precision high risk is at 9%.
- Precision low risk is at 100%.
- Recall high risk is at 89%.
- Recall low risk is at 94%.

![Adaboost_classifier](https://user-images.githubusercontent.com/80054925/125203233-3bdaa780-e23d-11eb-8ed7-739950cbc289.png)

## Summary
We are trying to find the best model that detects which loans are the highest and lowest risks. The accuracy test's of the first four models are lower compared to the BalancedRandom Forest and Adaboost models. Since you usually want a good balance of precision and recall, I recommend choosing the Easy Ensemble AdaBoost Classifier model to predict high risk loans. This model has the best balance due to its high accuracy score and good balance of precision and recall risks. 
