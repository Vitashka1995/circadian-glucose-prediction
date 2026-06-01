# Circadian-Glucose Prediction

This project uses interpretable machine learning to predict fasting blood glucose from NHANES 2017–2020 data using metabolic, hormonal, lifestyle, nutritional, demographic, and circadian-related variables.

## Project Summary

We developed and evaluated a series of leakage-resistant machine-learning pipelines to study which predictors of fasting blood glucose are recovered when conventional metabolic markers and circadian-related variables are considered jointly.

The final compact model, **Model 5b (XGBoost (+ Interactions, Selected, Pruned))**, achieved strong performance on the independent test set (**R² = 0.7761, MAE = 0.0804, RMSE = 0.1148**) using 10 predictors. Glycohemoglobin (HbA1c; labelled as GHB in model outputs) was the dominant predictor. The engineered interaction **Sleep Midpoint × Age** was consistently retained in the compact full-model pipeline, but its contribution was modest relative to dominant glycaemic and metabolic predictors.


## Contents

- `InvestigatingPredictorsFastingGlucose.ipynb`: Full code for data processing, feature engineering, and modeling
- `requirements.txt`: Python dependencies
- `data/README.md`: Describes the NHANES data source and access info

## License

MIT License

## Data Source

Data from NHANES: https://wwwn.cdc.gov/nchs/nhanes/



