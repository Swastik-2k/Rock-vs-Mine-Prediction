##Rock vs Mine Prediction

This project is focused on predicting whether an object is a rock or a mine based on sonar data using logistic regression. The dataset contains readings from sonar signals bounced off a metal cylinder (mine) and rocks at various angles and under various conditions.

## Dataset Description

The dataset used in this project contains 208 observations and 61 attributes, with the last attribute being the target variable indicating whether the object is a "R" (Rock) or "M" (Mine). The features represent the strength of the sonar signal at different frequencies.

## Data Preprocessing

- Loaded the dataset into a pandas DataFrame.
- Explored the dataset's shape and statistical summary.
- Checked the distribution of classes in the target variable.
- Explored the mean values of features grouped by the target variable.

## Model Building

- Separated the features (X) and target variable (Y).
- Split the data into training and testing sets.
- Utilized logistic regression for model training.
- Evaluated the model's performance on both training and testing data.

## Model Evaluation

- Achieved an accuracy of approximately 83.42% on the training data.
- Obtained an accuracy of around 76.19% on the test data.

## Predictive System

Implemented a predictive system using the trained logistic regression model to predict whether a given input represents a rock or a mine based on sonar data.

## Usage

To use this code:
1. Ensure you have the required libraries installed, including NumPy, pandas, and scikit-learn.
2. Download the dataset and update the file path accordingly.
3. Run the code to train the model and make predictions.
