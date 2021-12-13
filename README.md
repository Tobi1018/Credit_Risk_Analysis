# Credit_Risk_Analysis
## Project Overview

The purpose of this project is to analyze the credit card credit dataset from LendingClub, a peer-to-peer lending services company, Then using oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over-and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier, and EasyEnsembleClassifier, to predict credit risk. 

# Deliverable 1: Use Resampling Models to Predict Credit Risk.
Using my knowledge of the imbalanced-learn and scikit-learn libraries, I evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. Use the oversampling RandomOverSampler and SMOTE algorithms, and then use the undersampling ClusterCentroids algorithm. Using these algorithms, I resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

# Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
Using my knowledge of the imbalanced-learn and scikit-learn libraries, I used a combinatorial approach of over-and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, I resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## RandomOversampling
![ram1](https://user-images.githubusercontent.com/58860105/145740329-532eab4e-b00e-44e4-9b2a-289e48b8c755.PNG)

![ram2](https://user-images.githubusercontent.com/58860105/145740336-4b5c4619-ba9a-4c3a-9f8c-39dd3e2d54cd.PNG)

![ram3](https://user-images.githubusercontent.com/58860105/145740344-6f138e1b-17a4-47c2-88b7-a737b7932c11.PNG)




## SMOTE Oversampling
![smotth1](https://user-images.githubusercontent.com/58860105/145740134-25c8227c-9b32-43b3-a58e-9eaacb9ebeaf.PNG)

![smotth2](https://user-images.githubusercontent.com/58860105/145740135-4d69add9-6531-444c-b0c9-86470c3f6a7e.PNG)

![smotth3](https://user-images.githubusercontent.com/58860105/145740147-9d66f827-1c6a-4fae-b926-f878e2937a44.PNG)




## Undersampling
![undersamp1](https://user-images.githubusercontent.com/58860105/145739757-d2043743-c4d0-4a65-ab1e-8029d48ca087.PNG)

![undersamp2](https://user-images.githubusercontent.com/58860105/145739759-dd330879-2c1f-4ce4-aba8-003c85636dac.PNG)

![undersamp3](https://user-images.githubusercontent.com/58860105/145739763-675a8168-d037-4673-ae7b-bfc05afd56bd.PNG)


## Combination Sampling 
![Cmbinesmapling1](https://user-images.githubusercontent.com/58860105/145739532-5bcbeee4-dc4e-410f-9ab8-2370a631e713.PNG)

![Cmbinesmapling2](https://user-images.githubusercontent.com/58860105/145739540-72abd4a7-e890-418f-844f-0c2b812bf1c6.PNG)

![Cmbinesmapling3](https://user-images.githubusercontent.com/58860105/145739544-bc825d5f-f77b-41a6-89fa-6eb80a72610d.PNG)


## Balanced Random Forest Classifier
![balance1](https://user-images.githubusercontent.com/58860105/145740510-317bbfab-5347-4653-8672-6ee0054fae0a.PNG)

![balance2](https://user-images.githubusercontent.com/58860105/145740519-3d120029-7a81-4961-9e4e-8a990c9ce2a6.PNG)

![balance3](https://user-images.githubusercontent.com/58860105/145740527-b9ab8418-880e-47f5-8791-00a7f60e2e69.PNG)



## Easy Ensemble AdaBoost Classifier
![nwe1](https://user-images.githubusercontent.com/58860105/145741366-d0c2662f-6358-45a2-9ffd-e29926365e56.PNG)

![nwe2](https://user-images.githubusercontent.com/58860105/145741373-a64aff0e-083e-4989-a629-19a145c962c9.PNG)

![nwe3](https://user-images.githubusercontent.com/58860105/145741379-2a250b29-1b46-406a-bc09-09f78070eff7.PNG)



### Summary
  * To determine which model is best at predicting high-risk loans, we undersampled, oversampled, and combined both. Using ensemble classifiers, we resampled the data using the next two models in order to predict which loans are high or low risk. Oversampling, undersampling, and mixed models have low recall and our accuracy score is not as high as ensemble classifiers.
### Recomedation
  * I would suggest using the ensemble classifiers over the models. Easy Ensemble had the best balance of all the models because of its high accuracy score and a good balance of precision and recall scores.
