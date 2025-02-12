# Chennai-House-Price-Prediction

## Project Overview
This project aims to predict house prices in Chennai using various regression models. The dataset contains details about properties, and the goal is to build a predictive model to estimate house prices based on features like location, area, and other relevant factors.

## Project Structure
Chennai.csv: The dataset used for training and testing the model.

chennai house prediction.py: Python script for preprocessing the data, building models, and evaluating their performance.

chennai house prediction.ipynb: Jupyter notebook with detailed analysis and visualization (if available).

## Workflow Summary
### 1. Data Preprocessing:
Encoded categorical variables (e.g., Location).

Removed missing values and handled outliers.

Scaled and transformed features for better model performance.

### 2. Model Training:
Trained multiple regression models, including:

Linear Regression

Ridge Regression

Decision Tree Regressor

Random Forest Regressor

### 3. Model Evaluation:
Used r2_score and visualized actual vs. predicted values for model comparison.

## Results
The models were evaluated, and the Random Forest Regressor showed the best performance with the highest R² score.

Sample R² Scores:

Linear Regression: X

Ridge Regression: X

Decision Tree: X

Random Forest: X

## Visualizations
The project includes scatter plots to show the relationship between actual and predicted prices for each model, helping to compare their accuracy.

## Technologies Used
Python 

Pandas, NumPy, Scikit-learn

Matplotlib, Seaborn

TensorFlow

## Future Work
Improve accuracy using hyperparameter tuning.

Deploy the model as a web application for real-time predictions.

Use additional features to enhance predictions.

