# Supervised Machine Learning Models

This repository contains implementations of three supervised machine learning algorithms: Linear Regression, Logistic Regression, and Decision Trees. These models are trained on two different datasets. The Linear Regression model is trained on a medical charges dataset to predict medical charges, while the Logistic Regression and Decision Trees models are trained on the WeatherAUS dataset from Kaggle to predict whether it will rain tomorrow.

## Repository Structure

- `LinearRegression.py`: Implementation of the Linear Regression algorithm, trained on the medical charges dataset.
- `LogisticRegression.py`: Implementation of the Logistic Regression algorithm, trained on the WeatherAUS dataset.
- `DecisionTrees.py`: Implementation of the Decision Trees algorithm, trained on the WeatherAUS dataset.

## Linear Regression on Medical Charges Dataset

### Data Preprocessing and Model Training
The `LinearRegression.py` script performs the following steps:
- Loads and preprocesses the medical charges dataset:
  - Handles missing values.
  - Encodes categorical variables.
  - Normalizes numerical features.
- Applies the Linear Regression algorithm to predict medical charges.
- Outputs the regression results.

### Usage
To run the Linear Regression model on the medical charges dataset:
```bash
python LinearRegression.py
```

## Logistic Regression on WeatherAUS Dataset

### Data Preprocessing and Model Training
The `LogisticRegression.py` script performs the following steps:
- Loads and preprocesses the WeatherAUS dataset:
  - Handles missing values.
  - Encodes categorical variables.
  - Normalizes numerical features.
- Applies the Logistic Regression algorithm to predict whether it will rain tomorrow.
- Outputs the classification results.

### Usage
To run the Logistic Regression model on the WeatherAUS dataset:
```bash
python LogisticRegression.py
```

## Decision Trees on WeatherAUS Dataset

### Data Preprocessing and Model Training
The `DecisionTrees.py` script performs the following steps:
- Loads and preprocesses the WeatherAUS dataset:
  - Handles missing values.
  - Encodes categorical variables.
  - Normalizes numerical features.
- Applies the Decision Trees algorithm to predict whether it will rain tomorrow.
- Outputs the classification results.

### Usage
To run the Decision Trees model on the WeatherAUS dataset:
```bash
python DecisionTrees.py
```

## Dependencies
Make sure you have the following packages installed:
- pandas
- numpy
- scikit-learn

You can install the dependencies using the following command:
```bash
pip install pandas numpy scikit-learn
```

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

