# Online Food Delivery Customer Behavior Analysis and Prediction Using AI

## Project Overview

This project analyzes customer behavior using an online food delivery
dataset and applies machine learning to predict whether a customer will
order food online.

The project follows an end-to-end data analytics and machine learning
workflow, including data cleaning, exploratory data analysis, feature
preprocessing, classification, model evaluation, prediction, and feature
importance analysis.

## Objectives

- Analyze customer characteristics and online food-ordering behavior.
- Clean and preprocess the dataset.
- Perform exploratory data analysis using visualizations.
- Prepare categorical and numerical features for machine learning.
- Train classification models.
- Compare Logistic Regression and Random Forest.
- Evaluate models using multiple classification metrics.
- Predict online food-ordering behavior for a new customer.
- Analyze feature importance from the Random Forest model.

## Dataset

The project uses an online food delivery customer dataset containing
demographic, socioeconomic, educational, family, customer-type, geographic,
and feedback-related attributes.

The target variable is:

`Output`

Possible values:

- `Yes` — customer orders food online
- `No` — customer does not order food online

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected data types and dataset structure.
3. Checked missing values.
4. Checked duplicate records.
5. Removed exact duplicate observations.
6. Removed the redundant `Unnamed: 13` column.
7. Cleaned whitespace from categorical values.
8. Standardized the relevant occupation label.
9. Separated features and target variable.
10. Applied One-Hot Encoding to categorical features.

## Exploratory Data Analysis

The project includes visual analysis of:

- Online food-ordering distribution
- Age distribution
- Gender
- Occupation
- Monthly income
- Customer type
- Customer feedback
- Educational qualification
- Family size

These visualizations are used to understand patterns and relationships
within the dataset.

## Machine Learning

Two classification models were developed:

### Logistic Regression

Used as a baseline classification algorithm for predicting the binary
target variable.

### Random Forest

An ensemble classification algorithm using multiple decision trees to
model potentially complex relationships between customer attributes and
online ordering behavior.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The project also includes a model-performance comparison.

## AI-Based Prediction

The trained Random Forest model is used to predict online food-ordering
behavior for a sample customer.

The prediction includes:

- Predicted class
- Model-estimated class probabilities

## Feature Importance

Random Forest feature importance is analyzed to identify attributes that
were relatively useful to the model when distinguishing between the target
classes.

Feature importance is interpreted as a model-level measure and not as
evidence of a causal relationship.

## Project Structure

```text
Internship project/
│
├── Data/
│   └── online food delivery dataset.csv
│
├── Online_Food_Delivery_Analysis.ipynb
│
├── requirements.txt
│
└── README.md
