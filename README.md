# Loan Approval Prediction Using Machine Learning

This project leverages Machine Learning techniques to predict loan approval based on a dataset of applicant details. The aim is to help financial institutions make better decisions in loan processing by automating and improving the prediction process.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Contributing](#contributing)

## Introduction

Loan approval is a critical process for financial institutions, involving the evaluation of applicant details to determine the likelihood of loan repayment. This project builds a predictive model that can streamline this process by classifying loan applications as approved or rejected.

## Features

- Exploratory Data Analysis (EDA) for identifying patterns and trends.
- Data preprocessing to handle missing values, encode categorical variables, and normalize data.
- Machine Learning model training and testing for predictive analytics.
- Metrics evaluation to measure model performance.
- Easy-to-use interface for predictions.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Model**:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Support Vector Machine (SVM)

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
        git clone https://github.com/RushdaMansuri/Loan-Approval-Prediction-ML.git
        cd Loan-Approval-Prediction-ML
   ```

2. Set up a virtual environment (optional but recommended):

   ```bash
       python -m venv venv
       source venv/bin/activate  # For Linux/Mac
       venv\Scripts\activate   # For Windows
   ```

3. Install the required dependencies.

4. Run the Project.

## Usage:

1. Prepare your dataset (or use the provided dataset in the repository).
2. Preprocess the data using the included scripts or as part of the main.py.
3. Train the model and evaluate its performance.
4. Use the model to predict loan approval for new applicants.

## Dataset

- Source: [Provide the source of the dataset, if applicable]
- Description: The dataset includes applicant details such as income, education, employment status, credit history, and more. Labels indicate whether the loan was approved or not.
- Preprocessing Steps:
  - Handle missing values
  - Encode categorical variables
  - Normalize numerical features

## Model Details

- The project tests multiple machine learning algorithms:

  - Logistic Regression for binary classification.
  - Random Forest for robust and accurate predictions.
  - Decision Tree for interpretable results.
  - Support Vector Machine (SVM) for high-dimensional classification.

- Performance is evaluated using metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1-score

# Contributing

Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a feature branch:

   ```bash
       git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
       git commit -m "Add feature-name"
   ```

4. Push to the branch:

   ```bash
       git push origin feature-name
   ```

5. Create a Pull Request.
