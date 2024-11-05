# Obesity-classification

Currently working on it, will be updated once the project scope is reached.

Key Aspects of the project:
1) The problem statement is to classify whether a patient will suffer from Obesity or not. This is a multiclass problem where the classes are Insufficient weight, Normal weight, Overweight-I, Overweight-II, Obesity-I, Obesity-II, Obesity-III
2) Please refer to the notebook for extensive insights on EDA and Feature engineering
3) Experimented with Logistic, Random Forest, XGBoost, and CatBoost models
4) Optimized the hyperparameter tuning process using `Optuna` (based on Bayesian optimization) and found a significant boost in tuning time compared to `GridSearchCV`
5) Used Optuna visuals to interpret the best hyperparameters and their impact
6) SHAP to dissect the model predictions (working on it)
