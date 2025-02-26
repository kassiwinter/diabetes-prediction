# Diabetes Prediction

This repository contains an end-to-end machine learning project aimed at predicting the likelihood of diabetes based on user-provided health data. The project demonstrates the full machine learning pipeline from data gathering to model deployment using a Flask web application hosted on Heroku.

## Project Overview

The goal of this project is to create a seamless process for predicting diabetes by building a machine learning model that analyzes various health parameters. The web application takes user input, processes the data through the model, and provides the prediction result on a new page.

## Project Objectives

The project follows these key steps:

1. Data Gathering: Collected relevant medical data from various sources, including public datasets.
2. Descriptive Analysis: Explored the dataset to understand the underlying patterns and trends.
3. Data Visualizations: Created insightful visualizations to represent key relationships in the data.
4. Data Preprocessing: Cleaned and transformed the data for use in the machine learning model.
5. Data Modelling: Trained a machine learning model using scikit-learn to predict diabetes.
6. Model Evaluation: Assessed the model's performance using various metrics to ensure accuracy.

## Machine Learning Model

- Library: scikit-learn
- Algorithms Used: Logistic Regression, Decision Trees, Random Forests (or any chosen algorithms based on your project)
- Input Features: The following fields are taken from the user:
  1. Number of Pregnancies
  2. Insulin Level
  3. Age
  4. Body Mass Index (BMI)
  5. Blood Pressure
  6. Glucose Level
  7. Skin Thickness
  8. Diabetes Pedigree Function
  9. Output: The model predicts whether the person is likely to have diabetes (Yes/No)
- Framework: Flask
- Functionality:
  1. The user provides health-related data via a form.
  2. After submitting the form, the model processes the data and presents the prediction on a new page.

## Prerequisites

Python 3.13
Flask
scikit-learn
Pandas
Installation

