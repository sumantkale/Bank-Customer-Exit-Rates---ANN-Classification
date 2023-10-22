# Bank Customer Churn Prediction using Artificial Neural Networks (ANN)

## Description
This project focuses on predicting customer churn in a bank using an Artificial Neural Network (ANN) classification model. The code provided demonstrates the process of loading, exploring, preprocessing, and analyzing a dataset related to bank customers. The goal is to identify customers who are likely to exit or leave the bank based on various features.

## Table of Contents
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Transformation](#data-transformation)
- [Data Balancing](#data-balancing)
- [Model Building](#model-building)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Confusion Matrices and Classification Reports](#confusion-matrices-and-classification-reports)

## Project Structure
- `Bank Customer Exit Rates - ANN Classification.ipynb`: Jupyter Notebook containing the code.
- `Churn_Modelling.csv`: Dataset used for analysis.

## Dependencies
- Python 
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, keras

## Usage
1. Clone this repository to your local machine.
2. Open the Jupyter Notebook `Bank Customer Exit Rates - ANN Classification.ipynb`.
3. Run the code cells step by step to understand and reproduce the project.
4. Ensure you have the required libraries installed.

## Data Exploration
The project begins with data exploration to understand the dataset's characteristics.

## Data Preprocessing
Data preprocessing includes handling missing values, data type conversion, and dropping unnecessary columns.

## Exploratory Data Analysis (EDA)
Various visualizations are used to explore relationships between different features and the 'Exited' target variable.

## Data Transformation
Categorical variables are one-hot encoded, and the dataset is divided into input features and the target variable.

## Data Balancing
Data balancing is performed using RandomOverSampler to address class imbalance.

## Model Building
An Artificial Neural Network (ANN) model is created using Keras with multiple layers and activation functions.

## Model Training
The model is trained with 100 epochs and batch size of 20, validated on test data.

## Model Evaluation
The code evaluates the model's performance on both training and test data, reporting loss and accuracy metrics.

## Confusion Matrices and Classification Reports
Confusion matrices and classification reports are generated for the training and test data, providing precision, recall, and F1-score for each class.

Feel free to reach out for any questions or assistance with the project.

