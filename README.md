# Heart Disease Prediction

This repository contains a machine learning project aimed at predicting heart disease using various classification algorithms. The dataset used is sourced from the UCI Machine Learning Repository.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Evaluation](#models-and-evaluation)
- [Best Model](#best-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Heart disease is one of the leading causes of death globally. Early prediction can help in taking preventive measures to reduce the risk. This project utilizes machine learning techniques to predict the presence of heart disease in patients based on various medical attributes.

## Dataset

The dataset used in this project is the Heart Disease dataset from the UCI Machine Learning Repository. It contains 14 features, including age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

## Installation

To get started with this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the dataset in the `data` directory.
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Heart\ Disease\ Prediction.ipynb
    ```
3. Follow the steps in the notebook to train and evaluate the models.

## Models and Evaluation

The following models were trained and evaluated in this project:

- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Machine
- K-Nearest Neighbors
- Logistic Regression

The models were evaluated based on their accuracy on the test set.

## Best Model

The best performing model was the **Random Forest Classifier** with an accuracy of approximately 98.54%.

## Results

The Random Forest Classifier was the best model with the following accuracy:

```plaintext
Random Forest Accuracy: 0.9853658536585366
Gradient Boosting Accuracy: 0.9317073170731708
Support Vector Machine Accuracy: 0.8878048780487805
K-Nearest Neighbors Accuracy: 0.8341463414634146
Logistic Regression Accuracy: 0.7951219512195122
