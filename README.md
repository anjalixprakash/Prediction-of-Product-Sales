# Prediction-of-Product-Sales
Anjali Prakash

### Business Problem: 
For this project, we'll be using different features from the sale's prediction data set (such as outlet features and item features) to help determine outlet sales.

### Exploratory Data Analysis: 

![image](https://github.com/anjalixprakash/Prediction-of-Product-Sales/assets/134672983/c70d6fc2-3515-47ef-86a8-d1a8a7fc4ada)

### Explanatory Data Analysis: 

![image](https://github.com/anjalixprakash/Prediction-of-Product-Sales/assets/134672983/54f3104e-cd3f-4bb8-8eda-1b011602ca24)

## Models Evaluated & Results:

* Linear Regression Model
  Results for training data:
  - R^2 = 0.675
  - MAE = 730.734
  - MSE = 961248.703
  - RMSE = 980.433

Results for testing data:
  - R^2 = -6.01260861352168e+20
  - MAE = 4646805587119.512
  - MSE = 1.684127780903183e+27
  - RMSE = 41038125942873.94

* Random Forest Model
  ------------------------------------------------------------
Regression Metrics: Training Data
------------------------------------------------------------
- MAE = 298.805
- MSE = 185,445.986
- RMSE = 430.634
- R^2 = 0.937

------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 776.693
- MSE = 1,246,500.507
- RMSE = 1,116.468
- R^2 = 0.555

* Tuned Random Forest Model
  Training Scores for Random Forest Model
Results for training data:
  - R^2 = 0.936
  - MAE = 300.844
  - MSE = 189862.154
  - RMSE = 435.732



Testing Scores for Random Forest Model
Results for testing data:
  - R^2 = 0.55
  - MAE = 780.903
  - MSE = 1259123.507
  - RMSE = 1122.107

**Final Recommendations**

Based on the following insights, I would recommend using the random forest model to help determine our target, or product sales. 
