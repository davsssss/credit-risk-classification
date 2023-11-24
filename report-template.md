# Module 12- Credit Risk Classification

## Overview of the Analysis

This project is a linear regression model designed to determine creditworthiness of borrowers. It is designed to practice using different techniques in machine learning in order to obtain an ideal model. Two models are created and the goal is to determine the better model. The values we will be focusing on is healthy loans(0) and high risk loans(1).

## Results

* Machine Learning Model 1:
  * This model uses the original data and does fairly well with an accuracy of .94. It had a recall and precision score of 1.00, giving the impression of a good   
    model. The main issue with this model is when it comes to high risk loans where it only has an accuracy of 0.87, which could be improved.

* Machine Learning Model 2:
  * This model uses resampled data to train our model on. It has an accuracy, precision, and recall score of 1.00. The recall score of this model improved to one indicating that everyone that was expected to be high risk loan was labeled as such. The only issue is some that arent high risk loans were declared to be high risk.

## Summary

Neither model is perfect, but I would recommend Model 2 if I had to. It performs much better than Model 1 when it comes the the main goal, which is determining those who are high risk loans. The only real issue that could be improved on Model 2, is there are some people that are not high risk loans being declared as such.
