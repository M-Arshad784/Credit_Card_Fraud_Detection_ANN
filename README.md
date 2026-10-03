# Credit Card Fraud Detection using ANN

## Overview

This project focuses on **credit card fraud detection using an Artificial Neural Network (ANN)**.

The model is trained to analyze credit card transaction data and classify transactions as **legitimate or fraudulent**.

The project uses the **creditcard** dataset for training and evaluating the ANN model.

## Dataset

The dataset used in this project is **creditcard**.

The dataset contains credit card transaction records with transaction-related features and a target class indicating whether a transaction is legitimate or fraudulent.

### Dataset Download

The **creditcard dataset is not included in this repository** because of its large size.

You can download the dataset yourself from **Kaggle** and place the downloaded dataset in the project folder.

After downloading, make sure the dataset file is available in the project directory before running the notebook.

> **Dataset:** `creditcard`

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Artificial Neural Network (ANN)
* Deep Learning
* Machine Learning

## Project Workflow

1. Download the **creditcard** dataset.
2. Load the transaction data.
3. Explore and analyze the dataset.
4. Check for missing values.
5. Preprocess the transaction features.
6. Handle the imbalanced classes.
7. Split the dataset into training and testing sets.
8. Build an Artificial Neural Network.
9. Train the ANN model.
10. Evaluate the model.
11. Make predictions on test transactions.
12. Analyze fraud detection performance.

## ANN Model

The project uses an **Artificial Neural Network (ANN)** to classify credit card transactions.

```text
Credit Card Transactions
          ↓
Data Preprocessing
          ↓
Feature Scaling
          ↓
Training Data
          ↓
      ANN Model
          ↓
      Prediction
          ↓
Legitimate / Fraudulent
```

## Classification

The model performs binary classification:

```text
0 → Legitimate Transaction
1 → Fraudulent Transaction
```

## Key Learning

This project provided practical experience with:

* Artificial Neural Networks
* Binary Classification
* Fraud Detection
* Data Preprocessing
* Feature Scaling
* Imbalanced Datasets
* Model Training
* Model Evaluation
* Deep Learning
* TensorFlow and Keras

## Project Structure

```text
Credit_Card_Fraud_Detection_ANN/
│
├── Credit-Card-Fraud-Detection-ANN.ipynb
├── creditcard.csv
├── README.md
└── requirements.txt
```

> The `creditcard.csv` dataset is not included in this repository. Download it separately and place it in the project folder.

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/M-Arshad784/Credit_Card_Fraud_Detection_ANN.git
```

### 2. Download the Dataset

Download the **creditcard** dataset from Kaggle and place the dataset file inside the project folder.

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Open:

```text
Credit-Card-Fraud-Detection-ANN.ipynb
```

and run the cells step by step.

## Future Improvements

* Improve fraud detection performance.
* Experiment with different ANN architectures.
* Apply advanced techniques for handling class imbalance.
* Compare ANN with other machine learning models.
* Add precision, recall, F1-score, and ROC-AUC analysis.
* Deploy the fraud detection model as a web application.

## Author

**M Arshad**

GitHub: **M-Arshad784**
