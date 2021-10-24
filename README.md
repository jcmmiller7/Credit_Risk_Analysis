# Credit_Risk_Analysis

## Overview of Analysis

### The credit risk variable is very challenging for banks to predict when they issue loans to consumers. The purpose of the module is to look at factors within the loan stats data that help determine the credit risk of an individual. Certain factors tend to predict wheter a certain consumer is of bad or good credit. This is done by splitting the data into test and train sets. Models are then developed to take test data and train that model on a new data set in order to see the accuracy of prediction on the new data. SMOTE, Imbalanced Learned and other alorgithms are used to make the predictions happen. Some algorithms will oversample and some will undersample. THus, our goal is to find the model that best minimizes bias and this is doen with the balanced random forest classier and easy ensemble classifier. 


## Results

### Naive Random Sampling: The balanced accuracy score is around 67% and their is a extremely low positivity score of 1% for high risk individuals with 74% recall rate. 



<img width="946" alt="Screen Shot 2021-10-24 at 3 56 52 PM" src="https://user-images.githubusercontent.com/85506567/138610609-4a30a774-69b5-4da8-afe6-f9d8deac241d.png">


### Smote Oversampling: Balcanced accuracy score for the SMOTE model is 66% with a low positvity rate for high risk individuals at 1% with a 69% recall rate.
<img width="926" alt="Screen Shot 2021-10-24 at 3 59 48 PM" src="https://user-images.githubusercontent.com/85506567/138610694-33817f7f-fdf4-49c8-9912-1c84882597fd.png">


### Undersampling:



### Combination Sampling:

## Summary
