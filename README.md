# Predictive Analytics in Real Estate: Housing-Price-Estimation
## Overview & Objectives
### Business Challenge

In a real estate consultancy with a diverse clientele including developers, agents, and investors, setting accurate prices is crucial. Traditionally, the task of valuing properties has been the responsibility of appraisers, who must follow stringent criteria to ensure fairness for both buyers and sellers.
The critical question for our clients, upon receiving an appraisal, is determining if the property's "true value" aligns with or deviates from the appraised value. Our consultancy aims to leverage data to provide a reliable and efficient solution to this question. We have acquired a comprehensive dataset of historical housing transactions in Ames, Iowa, encompassing about 80 different attributes for each property, such as size, condition, and presence of a backyard, among others. The goal is to develop a predictive model that can estimate a property's market value based on its characteristics.

## Approach
### Classification Task

  Objective: Develop a classification model to determine if a house is considered expensive.
  Evaluation: The model in a classification task, means you can either make a correct prediction or an incorrect one. 

### Classification Steps:
housing_prices_classification: Includes steps from intuition-based modeling techniques to the evaluation of model accuracy. This evaluation statistical metrics implemented to assess the model's performancewere the Confusion Matrix, F1 Score, and Cohen's Kappa Score. It was employed also a diverse set of predictive modeling techniques, including decision trees, K-nearest neighbors, Random Forest, and logistic regression. Additionally, the methodology integrates advanced data processing techniques, such as one-hot encoding and ordinal encoding, alongside optimization strategies like grid search.

### Regression Task
Objective: Build a regression model to predict a house's exact price.
Evaluation: Given the nature of regression, perfect accuracy is improbable; performance metrics will assess prediction closeness.

Regression Steps:

### Project Methodology

  * Initiate with an Intuition-Based Model as a baseline.
  * Data Cleaning and Preprocessing.
  * Division of Data into Training and Test Sets.
  * Pipeline Creation for Streamlined Processing.
  * Implementation of Predictive Algorithms.
  * Accuracy Evaluation and Adjustment.
  * Deployment of the Model for Test Data Predictions.
  * Final Review of Model Performance.
