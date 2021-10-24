# Credit_Risk_Analysis

## Overview of Analysis

### The credit risk variable is very challenging for banks to predict when they issue loans to consumers. The purpose of the module is to look at factors within the loan stats data that help determine the credit risk of an individual. Certain factors tend to predict wheter a certain consumer is of bad or good credit. This is done by splitting the data into test and train sets. Models are then developed to take test data and train that model on a new data set in order to see the accuracy of prediction on the new data. SMOTE, Imbalanced Learned and other alorgithms are used to make the predictions happen. Some algorithms will oversample and some will undersample. THus, our goal is to find the model that best minimizes bias and this is doen with the balanced random forest classier and easy ensemble classifier. 


## Results

### Naive Random Sampling: The balanced accuracy score is around 67% and their is a extremely low positivity score of 1% for high risk individuals with 74% recall rate. 



<img width="946" alt="Screen Shot 2021-10-24 at 3 56 52 PM" src="https://user-images.githubusercontent.com/85506567/138610609-4a30a774-69b5-4da8-afe6-f9d8deac241d.png">


### Smote Oversampling: Balanced accuracy score for the SMOTE model is 66% with a low positvity rate for high risk individuals at 1% with a 69% recall rate.
<img width="926" alt="Screen Shot 2021-10-24 at 3 59 48 PM" src="https://user-images.githubusercontent.com/85506567/138610694-33817f7f-fdf4-49c8-9912-1c84882597fd.png">





### Undersampling: Balanced accuracy score of 66.2% with a 99% precision rate and recall rate of 41% for high risk individuals.

<img width="970" alt="Screen Shot 2021-10-24 at 4 05 49 PM" src="https://user-images.githubusercontent.com/85506567/138610882-6f4046a3-7ad1-46b2-a83d-f92f7de441a4.png">





### Combination Sampling: Balanced accuracy score of 54% with 99% precision and recall rate of 57% for high risk individuals.

<img width="952" alt="Screen Shot 2021-10-24 at 4 06 28 PM" src="https://user-images.githubusercontent.com/85506567/138610905-78e5dff6-fb40-4a7b-a393-1b4269283d8d.png">

### Balanced Random Forest Classifier: Balanced accuracy score of 77% with 99% precision and a recall rate of 88%
<img width="1140" alt="Screen Shot 2021-10-24 at 4 11 03 PM" src="https://user-images.githubusercontent.com/85506567/138611057-914c415a-11f2-4738-81dc-56f2cba079d7.png">


### Easy Ensemble Classifier: Balanced accuracy score of 93% with high precision and high recall rate


<img width="979" alt="Screen Shot 2021-10-24 at 4 12 16 PM" src="https://user-images.githubusercontent.com/85506567/138611115-f1cd1f65-30b6-4ec3-aa71-9b1c3d6cfa66.png">

## Summary

The first four models all have lower balanced accuracy scores and vary rates of precision. The ensemble model and Balacned Random Forest provide better measures to gauge high and low risk credit individuals with the ensemble method having the highest accuracy score. Thus, I would recommend this model for use. 
