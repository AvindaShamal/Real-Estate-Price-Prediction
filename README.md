# Real-Estate-Price-Prediction
This project is a complete walkthrough of building a real estate price prediction website. We will use machine learning to predict home prices in Bangalore, India, and deploy the model on a web interface using Python Flask.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Requirements](#requirements)
- [License](#license)

## Introduction
This project walks through the step-by-step process of building a real estate price prediction website. We use the Bangalore home prices dataset from Kaggle to build a model using sklearn and linear regression. The final website allows users to input details such as square footage, number of bedrooms, etc., and receive a predicted home price.

The project covers key data science concepts including:

- Data loading and cleaning
- Outlier detection and removal
- Feature engineering
- Dimensionality reduction
- Hyperparameter tuning using GridSearchCV
- k-fold cross-validation

## Features
- **Price Prediction**: Predicts home prices in Bangalore based on user inputs.
- **Model Deployment**: The machine learning model is deployed using a Python Flask server.
- **Interactive Web Interface**: A user-friendly website where users can input home details to get predictions.

## Dataset
The model is trained on the Bangalore home prices dataset, which includes attributes such as:

- Square footage
- Number of bedrooms
- Number of bathrooms
- Location
- Price

The dataset can be obtained from Kaggle: [Bangalore Home Prices](https://www.kaggle.com/path-to-dataset)


## Model
The prediction model uses Linear Regression. The process includes:

- Data cleaning and preprocessing using Pandas and Numpy.
- Data visualization using Matplotlib.
- Building the model using Sklearn.
- Hyperparameter tuning with GridSearchCV.
- Model evaluation using k-fold cross-validation.
- Requirements

## Requirements:

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- Flask
- joblib
- HTML/CSS/JavaScript

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
