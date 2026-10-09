# Regression-Competition-House-Price-Prediction


## Overview
This project focuses on predicting house sale prices using machine learning regression techniques. It involves exploring the dataset, preprocessing features, training regression models, and evaluating their performance to understand how well the models predict house prices.

## Problem Statement
The goal is to build a machine learning model that predicts the sale price of a house based on its features. Since the target variable is a continuous numerical value, this is a supervised regression problem.

## Dataset
The dataset contains information about residential properties and their sale prices.

- **Target variable:** `SalePrice`
- **ID column:** `PID`
- **Task:** Predict the sale price of each property.

The dataset is used for data exploration, feature preprocessing, model training, and validation.

## Workflow

1. **Data Loading** – Load the training and test datasets.
2. **Exploratory Data Analysis (EDA)** – Analyze numerical and categorical features, distributions, missing values, and relationships with sale prices.
3. **Data Preprocessing** – Handle missing values and prepare categorical and numerical features.
4. **Feature Engineering** – Transform relevant features to improve model performance.
5. **Model Training** – Train regression models on the prepared data.
6. **Model Validation** – Evaluate model performance using a validation dataset.
7. **Prediction** – Generate house price predictions for unseen data.

## Models and Techniques
- Regression-based machine learning
- Random Forest Regressor
- CatBoost Regressor
- Feature preprocessing and engineering
- Train-validation split
- Model performance comparison

## Evaluation
Model performance is evaluated using the **Mean Squared Logarithmic Error (MSLE)**.

MSLE measures the difference between the logarithms of actual and predicted prices, making it useful when relative prediction errors matter.

Lower MSLE values indicate better performance.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- CatBoost

## Project Structure

    house-price-prediction/
    ├── README.md
    └── house_price_prediction.ipynb

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn catboost jupyter
   ```

3. Open the notebook in Jupyter Notebook or VS Code.
4. Run the cells sequentially.

## Key Learnings
- Performing exploratory data analysis on real-world datasets.
- Handling numerical and categorical features.
- Building and validating regression models.
- Comparing model performance using an appropriate evaluation metric.
- Understanding the machine learning workflow from data preprocessing to prediction.

## Future Improvements
- Experiment with additional regression algorithms.
- Perform hyperparameter tuning.
- Improve feature engineering.
- Use cross-validation for more reliable evaluation.
- Analyze feature importance and prediction errors.

