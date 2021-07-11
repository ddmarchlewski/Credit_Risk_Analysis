# Credit_Risk_Analysis
## Overview
In this project, we are asked to predict credit risk. We predict it by using Python to build machine learning models. We evaulate the data using the following models.
- Using SMOTE and RandomOverSampler to oversample the data.
- Using ClusterCentroids to undersample the data. 
- Using SMOTEENN to combine the oversample and undersample data. 
- Using BalancedRandomForestClassifier and EasyEnsembleClassifier, which reduce bias, and compare the two machine learning models. 

## Results
RandomOverSampler Module
- This module's accuracy test is 65%. 
- High_risk is low with 1%.
- Low_risk is 100%.
- Recall high risk is at 69%.
- Recall low risk is at 60%.

![oversampling](https://user-images.githubusercontent.com/80054925/125202478-675b9300-e239-11eb-9239-860c096a93de.png)

SMOTE Oversample
- This module's accuracy test is 66%.
- Hish_risk is low with 1%.
- Low_risk is 100%.
- Recall high risk is at 63%.
- Recall low risk is at 69%. 

![smote_sampling](https://user-images.githubusercontent.com/80054925/125202749-9fafa100-e23a-11eb-8d8e-8722ad8c67d0.png)

Cluster Centroid Undersampling
- This module's accuracy test is 66%
- High_risk is low with 1%
- Low_risk is 100%. 
- Recall high risk is at 69%.
- Recall low risk is at 40%.

![undersampling](https://user-images.githubusercontent.com/80054925/125202843-22d0f700-e23b-11eb-801b-7c2d67761

SMOTEENN Combination
- This module's accuracy test is 54%.
- High_risk is low with 1%.
- Low_risk is 100%.
- Recall high risk is at 72%.
- Recall low risk is at 57%.

![combined_sampling](https://user-images.githubusercontent.com/80054925/125202945-ae4a8800-e23b-11eb-9144-55a5fafacf8c.png)
