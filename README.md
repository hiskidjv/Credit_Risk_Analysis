# Credit_Risk_Analysis

## Overview of the analysis

>This challenge dives into a comparison of 6 different machine learning scripts that are trained to predict whether a loain will be "high risk".  For any of them to work, some data munging was required on our csv file.  This was necessary in order to encode string information into a numeric type.  So our months changed to numbered (1-5 for jan-may), and all categorial info was divided into separate columns with 1's indicating that category in use and 0's when a different category was in the original column.  Then, in every case, we had to follow the pattern of machine learning coding:
1. Defining the features and the target
2. Splitting the data into training and testing sets 
3. Fitting the data into a prediction model 
    --typically by training a logicstic regression classifier
    --often resampling the data to adjust for drastic imbalance in the target
4. Evaluating the classifier's prediction(s)
    --balanced accuracy score
    --confusion matrix
    --classification report

## Results: 

> Below are the results of each of the 6 tests we ran:

* RandomOverSampler-
![image_name](path/to/image_name.png).
* SMOTE-
![image_name](path/to/image_name.png).
* ClusterCentroids-
![image_name](path/to/image_name.png).
* SMOTEENN-
![image_name](path/to/image_name.png).
* BalancedRandomForestClassifier
![image_name](path/to/image_name.png).
* EasyEnsembleClassifier
![image_name](path/to/image_name.png).

### Description of Stats:  

## Summary
>best with recommendation