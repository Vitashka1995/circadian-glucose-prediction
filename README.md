# Circadian-Glucose Prediction

This project uses machine learning to predict fasting glucose levels using metabolic markers, lifestyle factors, and circadian rhythm measures.

## Project Summary

We developed a machine learning model based on NHANES 2017–2020 data to investigate the relationship between sleep patterns and glucose metabolism. The final XGBoost model achieved high accuracy (test R² = 0.7748, MAE = 0.0808) using only 10 key predictors, including an interaction term between **Sleep Midpoint × Age**.

## Contents

- `prediction_fasting_glucose.ipynb`: Full code for data processing, feature engineering, and modeling
- `requirements.txt`: Python dependencies
- `data/README.md`: Describes the NHANES data source and access info

## License

MIT License

## Data Source

Data from NHANES: https://wwwn.cdc.gov/nchs/nhanes/



