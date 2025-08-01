# Rainfall Prediction using Machine Learning

This project predicts whether it will rain or not based on various weather parameters. It uses a Random Forest Classifier to make the predictions.

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
