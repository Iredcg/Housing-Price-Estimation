# Predictive Analytics in Real Estate: Housing-Price-Estimation
## Overview & Objectives
### Business Challenge

In a real estate consultancy serving a diverse clientele of developers, agents, and investors, accurately setting property prices is paramount. Traditionally, property appraisals have been conducted by experts adhering to strict criteria, ensuring fairness for both buyers and sellers. A significant challenge arises when clients question if the appraised value truly reflects a property's market value. Our consultancy seeks to address this by leveraging a comprehensive dataset of historical housing transactions from Ames, Iowa, which includes around 80 attributes per property, such as size, condition, and the presence of a backyard. The aim is to develop a predictive model capable of estimating a property's market value based on its features.

## Approach
### Classification Task:
  
  Objective: Develop a model to classify houses as either "Expensive" (1) or "Not Expensive" (0), aiding in the understanding of affordability and market segmentation.
  
  Evaluation:Accuracy in classification tasks is binary; predictions are either correct or incorrect.

### Classification Steps:
This project segment, housing_prices_classification, aims to categorize houses based on their price. The approach includes a progression from intuition-based modeling to detailed evaluation of model accuracy. We utilize statistical metrics such as the Confusion Matrix, F1 Score, and Cohen's Kappa Score to assess performance. A variety of predictive modeling techniques, including decision trees, K-nearest neighbors, random forest, and logistic regression, are employed alongside advanced data processing methods like one-hot encoding and ordinal encoding. Optimization strategies such as grid search are also integrated.

### Regression Task:
  
  Objective: Construct a regression model to predict the exact price of a house.
  
  Evaluation: Absolute accuracy is unlikely in regression tasks; thus, metrics will measure how close predictions are to actual prices.

### Regression Steps:
The housing_prices_regression phase focuses on predicting house prices in dollars, marking a shift to a regression task. Data preparation involves MinMaxScaler, SimpleImputer, and OneHotEncoder, followed by the application of machine learning models like the DecisionTreeRegressor, KNeighborsRegressor, LinearRegression, and RandomForestRegressor. Various feature selection techniques and GridSearchCV for hyperparameter tuning are utilized. Model evaluation and prediction are based on r2_score and mean_squared_log_error metrics.

### Project Methodology

* Start with an Intuition-Based Model for an initial baseline.
* Conduct Data Cleaning and Preprocessing for optimal data quality.
* Split the data into Training and Test Sets for model validation.
* Create a Pipeline for efficient data and model processing.
* Implement Predictive Algorithms to explore different modeling approaches.
* Evaluate Accuracy and make necessary adjustments to improve model performance.
* Deploy the Model on Test Data to predict housing prices.
* Perform a Final Review of Model Performance to ensure reliability and accuracy.

