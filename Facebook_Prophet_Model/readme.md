# Predictive Analytics with Random Forest

This Collab Notebook demonstrates predictive analytics using a Random Forest model. It focuses on predicting income based on various features. Below is an overview of the project:

## Data Preparation

- The dataset used in this analysis is sourced from `marketing_campaign.csv`.
- Data types and shapes are checked, and missing values are examined and handled.
- Unwanted variables are removed, and categorical variables are transformed using one-hot encoding.
- Date of birth (DOB) is converted into age, and rows with missing data are dropped.
- The dataset is split into training and testing sets for model development and evaluation.

## Random Forest Model

- A Random Forest Regressor model is used to predict income.
- The model is trained with 300 decision trees.
- Predictions are made on the test dataset.

## Model Evaluation

- Model performance is assessed using Mean Absolute Error (MAE).
- Key features influencing income are visualized with feature importance plots.
- Parameter tuning is performed to optimize model performance.

## Results

- The Random Forest model's performance is evaluated, and the MAE is reported.
- Important features affecting income prediction are visualized.
- Parameter tuning results in the best hyperparameters for the model.

---

For detailed code and analysis, please refer to the Collab Notebook in this repository.

