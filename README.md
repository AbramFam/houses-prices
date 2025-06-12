# California Housing Price Prediction

This project builds a regression model to predict median house prices in California based on various housing and demographic features. The dataset comes from the California housing dataset and includes information like number of rooms, population, median income, and proximity to the ocean.

## Project Description

The project involves:
- Data loading and cleaning (handling missing values)
- One-hot encoding for categorical features (`ocean_proximity`)
- Feature selection and splitting into training/testing sets
- Training a Random Forest Regressor model
- Evaluating model performance using R² score

## Model Performance

The trained `RandomForestRegressor` model achieved an R² score of **0.82** on the test set, indicating good predictive performance.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-learn (RandomForestRegressor, train_test_split)
- Jupyter Notebook

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AbramFam/Titanic-servival.git
Navigate to the housing prices project directory.

Install dependencies (if needed):

bash


pip install pandas numpy scikit-learn
Run the Jupyter notebook or Python script.

Dataset
You can download the dataset from:
Kaggle - California Housing Prices

License
This project is licensed under the MIT License.
