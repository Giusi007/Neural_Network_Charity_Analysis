# Neural_Network_Charity_Analysis

## Purpose
The purpose of this analysis is to use deep learning neural networks with TensorFlow in Python to analyze charitable donations. The goal is to understand the success of the donations.

## Methods
The analysis was done with the following steps:
1. Preprocessing the data to be used in the neural network
2. Compiling, trainings, and evaluating the model
3. Utilizing various options (adding neurons, adding layers, changing the activation function) to optimize the model with a goal of >75% accuracy.

## Results
Columns EIN and NAME removed from the input data. IS_SUCCESSFUL determined as the target. Determined the features of the model and encoded them, then split them into training and testing datasets.

Even with three different optimization attempts, the model was not able to perform above 75% accuracy. This makes it not suitable to predict the success of charitable donations.

## Summary
We were not able to reach our target of 75% accuracy. The model is not performing at an acceptable accuracy to be used confidently. One further step that could be taken wiuold be to use a Random Forest Classifier to cmpbine decision trees and generate a classification output. We could then compare this to our current model.

