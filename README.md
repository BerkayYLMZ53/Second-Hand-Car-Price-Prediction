# 🚗 Used Car Price Prediction (Linear Regression)

This project is a machine learning study developed to predict the market selling price of used cars by analyzing their technical specifications and sales data. An end-to-end regression analysis workflow was implemented.

## 🎯 Project Objective
To analyze the impact of variables such as model year, mileage, fuel type, current new price, and transmission type on used car market values, and to build a model capable of predicting prices based on these features.

## 📊 Dataset and Preprocessing
The **"Vehicle Dataset"** obtained from Kaggle was used in this project. During the data preprocessing and modeling stages, a **Scikit-Learn Pipeline** architecture was utilized to ensure modular and clean code:
* **Feature Scaling:** `StandardScaler` normalization was applied to numerical features (such as age and mileage) to prevent scale disparities from affecting model training.
* **Categorical Transformations:** Textual features such as fuel type and transmission were encoded into numerical formats suitable for the model.

## 🛠️ Technologies and Methods Used
* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Algorithm:** Linear Regression

## 📈 Model Performance and Results
The trained model was evaluated on the test data, indicating its ability to capture the linear relationships between the independent variables and the target variable:
* **$R^2$ Score (Coefficient of Determination):** `0.8853` (88.5%) — The model accounts for approximately 88.5% of the variance in car prices.
* **MAE (Mean Absolute Error):** `1.23` — The model's price predictions deviate from the actual prices by an average of 1.23 units.

## 🚀 Running the Project Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/BerkayYLMZ5353/car-price-prediction.git
   ```
