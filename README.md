# signate-smbc
## Overview
- This is a portfolio project for the SIGNATE SMBC Group GREEN DATA Challenge, in which I implemented the full pipeline in Python—from preprocessing and model training to inference and submission file generation.

## Notebooks
- [`notebooks/01_train_main.ipynb`](notebooks/01_train_main.ipynb)：This is code for validating models on the training data, including LightGBM, bootstrap resampling, k-fold cross-validation, grid search, and CatBoost.
- [`notebooks/02_inference_main.ipynb`](notebooks/02_inference_main.ipynb)：evaluated performance on the test data using CatBoost and log transformation.

## Approach
- **Features**：FacilityName,Latitude,Longitude,LocationAddress,City,State,ZIP,County,FIPScode,PrimaryNAICS,SecondPrimaryNAICS,IndustryType,TRI_Air_Emissions_10_in_lbs,TRI_Air_Emissions_11_in_lbs,TRI_Air_Emissions_12_in_lbs,TRI_Air_Emissions_13_in_lbs,GHG_Direct_Emissions_10_in_metric_tons,GHG_Direct_Emissions_11_in_metric_tons,GHG_Direct_Emissions_12_in_metric_tons,GHG_Direct_Emissions_13_in_metric_tons,GHG_Direct_Emissions_14_in_metric_tons
- **Models**：LightGBM/CatBoost
- **Validation**：K-Fold/Grid Search/Bootstrap

## Notes
- Please place the data in your own environment (e.g., Google Colab) to run the code.
