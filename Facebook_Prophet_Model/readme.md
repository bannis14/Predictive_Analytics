# Predictive Analytics Using Facebook Prophet

## Overview

This repository contains the code and data for the "Facebook_Prophet_Model" project, which aims to forecast weekly shelter occupancy using the Prophet forecasting model. The project is implemented in a Google Colab notebook and includes data preprocessing, model training, evaluation, and hyperparameter tuning.

## Table of Contents

- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset (`DHS_weekly.csv`) consists of weekly shelter occupancy data, including the number of individuals in shelter and holiday indicators.

## Prerequisites

To run the notebook and reproduce the results, you'll need the following libraries and tools:

- Python 3.x
- Jupyter Notebook or Google Colab
- Required Python libraries (installable via `pip` or `conda`):
  - numpy
  - pandas
  - prophet
  - scikit-learn

## Usage

1. Clone this repository to your local machine or open it in Google Colab.
2. Ensure you have the required dataset (`DHS_weekly.csv`) in the project directory.
3. Open the `Facebook_Prophet_Model.ipynb` notebook in Jupyter Notebook or Google Colab.
4. Run the cells in the notebook sequentially to execute the data preprocessing, model training, evaluation, and hyperparameter tuning steps.
5. Analyze the results and customize the notebook for your specific forecasting tasks.

## Results

The project includes the following key results and visualizations:

- Data preprocessing: Conversion of date columns, renaming columns for Prophet.
- Holiday definition: Identification of Easter and Thanksgiving holidays.
- Model training: Training of the Prophet forecasting model with regressors.
- Evaluation: Calculation of Mean Squared Error (MSE) and visualizations of model components.
- Hyperparameter tuning: Grid search for Prophet model hyperparameters.

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull request. Contributions and suggestions are welcome!

## License

This project is licensed under the MIT License. See the [MIT LICENSE](LICENSE) file for details.
