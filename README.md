# Credit Card Fraud Detection with Machine Learning Using Logistic Regression and Autoencoder

This project aims to detect fraudulent transactions using a combination of logistic regression and an autoencoder for anomaly detection. The approach includes data preprocessing, feature scaling, model training, and evaluation.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Model Description](#model-description)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Fraud detection is crucial for financial institutions to prevent financial losses. This project provides a robust machine learning pipeline to identify fraudulent transactions effectively. It combines logistic regression and autoencoder techniques to enhance detection accuracy.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Xtley001/Credit Card Fraud Detection with Machine Learning Using Logistic Regression and Autoencoder.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Credit Card Fraud Detection with Machine Learning Using Logistic Regression and Autoencoder
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your dataset and ensure it includes a 'Class' column indicating non-fraud (0) and fraud (1).
2. Run the preprocessing script to scale the features:
    ```python
    python preprocess.py
    ```
3. Train the autoencoder:
    ```python
    python train_autoencoder.py
    ```
4. Train the logistic regression model:
    ```python
    python train_logistic_regression.py
    ```
5. Evaluate the models:
    ```python
    python evaluate_models.py
    ```

## Model Description

### Autoencoder
An autoencoder is trained on non-fraudulent transactions to learn normal transaction patterns. It helps in detecting anomalies by measuring reconstruction errors.

### Logistic Regression
A logistic regression model is trained on the transaction data to classify transactions as fraudulent or non-fraudulent.

## Evaluation

The models are evaluated using classification reports and accuracy scores. The performance metrics include precision, recall, f1-score, and overall accuracy.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss potential improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

