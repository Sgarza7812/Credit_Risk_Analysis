# Credit Risk Analysis

## Overview

The purpose of this analysis was to create a supervised machine learning model that could accurately predict credit risk. To complete this task, I used the following methods:
•	Naive Random Oversampling
•	SMOTE Oversampling
•	Cluster Centroid Undersampling
•	SMOTEENN Sampling
•	Balanced Random Forest Classifying
•	Easy Ensemble Classifying
Through each of these methods, I split my data into training and testing datasets, and compiled accuracy scores, confusion matrixes, and classification reports as my results.

## Results

Naive Random Oversampling Results: The accuracy score is 64%, the precision for the high risk has a very low positivity at 1% and the recall is 59%

![image](https://user-images.githubusercontent.com/78935982/124393706-610d6a00-dcc1-11eb-9229-fe8f1e12edac.png)

 
SMOTE Oversampling Results: The accuracy score is 63.4%, the precision for the high risk has a low positivity again at 1% and recall is 64% overall
 
 ![image](https://user-images.githubusercontent.com/78935982/124393715-67034b00-dcc1-11eb-9a55-2e37c7626c7c.png)


Undersampling Results: Accuracy score is 63.3%, the precision is at 99% and the recall is 43%

 ![image](https://user-images.githubusercontent.com/78935982/124393722-6b2f6880-dcc1-11eb-808a-6fedc0d33144.png)


Combination (Over and Undersampling) Results: Balanced Accuracy Score is 51.6%, the Precision is 99% and the recall is 57% overall

 ![image](https://user-images.githubusercontent.com/78935982/124393729-6ff41c80-dcc1-11eb-9107-b28f9e352ae6.png)


Balanced Random Forest Classifier Results: Accuracy Score of 76.1%, the Precision is 99% and the Recall is 89%

 ![image](https://user-images.githubusercontent.com/78935982/124393733-7387a380-dcc1-11eb-862f-b6bd8b788992.png)


Easy Ensemble AdaBoost Classifier Results: Accuracy score of 91.8%, the Precision is 99% and the Recall is 94%

 ![image](https://user-images.githubusercontent.com/78935982/124393736-78e4ee00-dcc1-11eb-96b1-bc1fb252e797.png)


### Summary

In the first four models we Undersampled, Oversampled and a combination of both to try and determine which model is best at predicting which loans are at highest risk. The last two models, I resampled the data using Ensemble Classifiers to try and predict which loans are at high or low risk. In the Under and Over Sample methods, the accuracy score and the recall are not as high as the ensemble classifiers. In the models you want a balance of recall and precision which is why I would recommend using the Ensemble Classifiers to predict the high or low risk. It appears that the Easy Ensemble had the best balance of all the models with its high accuracy score and good balance of precision and recall scores.
