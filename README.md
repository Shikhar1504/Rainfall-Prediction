# Rainfall Prediction using Machine Learning

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project focuses on predicting rainfall using various meteorological parameters through machine learning. It leverages a Random Forest Classifier, a powerful ensemble learning method, to analyze historical weather data and forecast whether it will rain. The goal is to provide an accurate and robust prediction model for rainfall events.

## Features

- **Rainfall Prediction**: Predicts rainfall based on historical weather data.
- **Machine Learning Model**: Utilizes a Random Forest Classifier for accurate predictions.
- **Data Preprocessing**: Handles various weather parameters including temperature, humidity, wind speed, and more.
- **Model Evaluation**: Provides evaluation metrics such as accuracy, confusion matrix, and classification report.
- **Jupyter Notebook**: Fully documented and runnable Jupyter Notebook for easy understanding and reproduction.

## Installation

To run this project, you need to have Python and the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- pickle5

You can install them using pip:

```
pip install -r requirements.txt
```

## Usage

1. Clone the repository.
2. Install the dependencies.
3. Open the `Rainfall_Prediction_using_Machine_Learning.ipynb` notebook in Jupyter Notebook or JupyterLab.
4. Run the cells in the notebook.

## Data

The data used in this project is in the `Rainfall.csv` file. It contains the following columns:

- day
- pressure
- maxtemp
- temparature
- mintemp
- dewpoint
- humidity
- cloud
- rainfall
- sunshine
- winddirection
- windspeed

## Model

The model used in this project is a Random Forest Classifier. The model is trained on the data in `Rainfall.csv` and then used to predict whether it will rain or not. The trained model is saved in a pickle file.

## Evaluation

The model is evaluated using the following metrics:

- Accuracy
- Confusion matrix
- Classification report

## Contributing

Contributions are welcome. Please open an issue or a pull request.

## License

This project is licensed under the MIT License.
