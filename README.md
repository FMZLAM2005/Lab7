# Lab7

# Logistic Regression Project

## Overview
This assignment focuses on applying Logistic Regression using an advertising dataset to predict whether a user clicks on an advertisement.

The assignment required completing the missing parts of the provided code and performing model training and evaluation.

## Dataset Features
The dataset includes:
- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Male
- Clicked on Ad

## Tasks Performed

### 1. Data Exploration
Used:
- head()
- info()
- describe()

to understand the dataset structure and features.

### 2. Exploratory Data Analysis (EDA)
Created visualizations including:
- Age histogram
- Jointplots
- KDE plots
- Pairplot with Clicked on Ad categories

### 3. Data Preparation
Selected important numerical features and split the dataset into:
- Training set
- Testing set

### 4. Logistic Regression Model
- Trained a Logistic Regression model using scikit-learn
- Used the training dataset for fitting the model

### 5. Predictions and Evaluation
Generated predictions on the testing data and evaluated the model using:
- Precision
- Recall
- F1-score
- Accuracy

## Results
The model achieved approximately 97% accuracy, showing excellent performance in predicting whether users clicked on advertisements.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
