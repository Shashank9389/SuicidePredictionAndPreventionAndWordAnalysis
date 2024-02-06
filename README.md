# SuicidePredictionAndPreventionAndWordAnalysis
A natural language processing project which determines whether a person is suicidal or not through his social media posts


## Overview

This project aims to predict suicidal content in text data using machine learning. The provided code includes data loading, preprocessing, model building, and exploratory data analysis (EDA). It utilizes a Random Forest Classifier to predict whether a given text is indicative of suicidal thoughts.


## Background

Mental health awareness is a crucial aspect of well-being. This project addresses the challenging task of identifying potentially suicidal content in text, contributing to efforts to provide timely support and intervention.

## Dataset

The dataset used for this project is the "Suicide_Detection.csv" file. It includes text data and corresponding labels for classifying whether the content is related to suicide. The dataset was preprocessed to extract relevant features for model training.


## Usage

- **Exploratory Data Analysis (EDA):** The notebook provides insights into the dataset, including visualizations of text length, word frequencies, and class distributions.

- **Model Building:** A Random Forest Classifier is used for predicting suicidal content. Hyperparameter tuning is available for optimization.

- **Prediction on New Data:** The script includes an example of predicting the class of a new text input.


## Procedure

Follow these specific steps to understand and replicate the key processes involved in the project:

### 1. Data Collection

- **Dataset:** The project utilizes the "Suicide_Detection.csv" dataset. This dataset is obtained from [Kaggle](https://www.kaggle.com/nikhileswarkomati/suicide-watch) and contains text data along with corresponding labels indicating whether the content is related to suicide.

### 2. Data Preprocessing

- **Loading Data:** The dataset is loaded into a Pandas DataFrame to facilitate data manipulation and analysis.
  
- **Handling Missing Values:** Check and handle any missing values in the dataset to ensure data completeness.

- **Text Length Analysis:** Explore the distribution of text lengths to understand the characteristics of the text data.

### 3. Data Description

- **Exploratory Data Analysis (EDA):** Conduct EDA to gain insights into the dataset. This includes visualizations such as count plots for class distribution, descriptive statistics, and word frequency analysis.

- **Feature Engineering:** Create additional features, such as word frequencies, to enhance the dataset for model training.

### 4. Model Development

- **Random Forest Classifier:** Utilize a Random Forest Classifier for predicting suicidal content. This involves setting up the model, exploring hyperparameter tuning (commented-out sections), and fitting the model to the training data.

### 5. Model Evaluation

- **Performance Metrics:** Evaluate the model using standard performance metrics such as accuracy, recall, and potentially other metrics depending on the project's objectives.

- **Feature Importance:** Examine feature importances to understand which words contribute most to the model's predictions.

### 6. Prediction on New Data

- **Use Case:** A snippet is provided to showcase how the trained model can be used to predict the class of a new text input.


