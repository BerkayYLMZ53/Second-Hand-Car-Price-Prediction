# Used Car Price Prediction with Linear Regression

An end-to-end machine learning project that explores how vehicle characteristics relate to used-car selling prices and builds a baseline regression model for price estimation.

## Project objective

The goal is to study the relationship between features such as model year, mileage, fuel type, transmission, and new-car price, and to estimate a used vehicle's selling price from those attributes.

## Dataset and preprocessing

The project uses the **Vehicle Dataset** from Kaggle. The workflow includes:

- Preparing numerical and categorical features.
- Scaling numerical variables with `StandardScaler`.
- Encoding categorical variables for model training.
- Combining preprocessing and estimation in a Scikit-learn Pipeline.

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Linear Regression

## Model evaluation

The reported test-set results in this project are:

| Metric | Result | Interpretation |
|---|---:|---|
| R² (coefficient of determination) | 0.8853 | The model explains approximately 88.53% of the variance in the test target values. |
| MAE (mean absolute error) | 1.23 | The average absolute prediction error is 1.23 units in the dataset's target-price scale. |

These are results from this project's experiment, not a guarantee of performance on other datasets or future market prices. The MAE unit follows the dataset's price unit; check the dataset documentation before interpreting it as a specific currency amount.

## Run locally

Clone this repository:

```bash
git clone https://github.com/BerkayYLMZ53/Second-Hand-Car-Price-Prediction.git
cd Second-Hand-Car-Price-Prediction
```

Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open the notebook:

```bash
jupyter notebook
```

## Notes

This is an educational machine learning project. Predictions should be interpreted as estimates from the selected dataset and model, not as professional vehicle valuations.
