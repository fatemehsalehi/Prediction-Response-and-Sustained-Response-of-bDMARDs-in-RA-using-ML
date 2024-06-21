# Prediction-Response-and-Sustained-Response-of-bDMARDs-in-RA-using-ML
Description
This repository contains the code used for the machine learning analysis described in the manuscript "Machine Learning Prediction of Treatment Response to Biological Disease-Modifying Antirheumatic Drugs in Rheumatoid Arthritis". The analysis involves data preprocessing, model trainings, and evaluation, and explainabe SHAP values.

Files
preprocess.ipynb: This notebook contains the processes for data cleaning, imputation, and labeling.

Description:
Cleaning: Handles missing data and outliers.
Imputation: Fills in missing values, using nao and MICE imputation
Labeling: Labels the data according to EULAR criteria for response (after 6months) and sustained response (after 12 months)
Note: The preprocessing steps can be modified based on the specific data and labeling criteria.


main.ipynb: This notebook is used for training and evaluating machine learning classifiers to predict treatment response.

Description:
Model Training: Uses nested cross-validation for model evaluation.
Feature Selection: Selects the most relevant features for the models.
SHAP Values: Utilized to interpret the model by showing the impact and direction of the best features.
Evaluation: Includes performance metrics and visualizations.


environment.yml: This file specifies the dependencies required to run the notebooks.

Description:
Contains a list of all packages and versions needed.
Used to create a conda environment with the exact dependencies.
