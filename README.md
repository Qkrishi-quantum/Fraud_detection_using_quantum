# Quantum Fraud Detection

## Overview

This GitHub repository contains two Jupyter notebooks that demonstrate the application of Quantum Machine Learning (QML) in fraud detection for credit card transactions and stock market. The notebooks leverage the power of quantum computing to enhance the accuracy and efficiency of fraud detection algorithms.

## Contents

1. [Credit Card Fraud Detection](QuantumFraudDetectiononCreditCardData.ipynb)
2. [Stock Fraud Detection](QuantumFraudDetectiononStocks.ipynb)

## Credit Card Fraud Detection

### Purpose

The primary goal is to advance fraud detection in credit card transactions using QML. 

These techniques applicable are not only applicable to credit card fraud but also to different domains like Anti Money Laundering, Escrow Fraud Detection, Loan Fraud Detection, and Transaction Fraud Detection.

### Method and Results

#### Dataset and Data Preprocessing

The credit card transaction dataset, obtained from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud), is highly imbalanced. To tackle this, we employ random under-sampling and feature selection techniques. The system aims to:

1. **Improve Fraud Detection Accuracy**: Utilizing QSVC and quantum feature maps, the system maps transactions into a higher-dimensional quantum space, enhancing pattern recognition for accurate fraud detection.

2. **Mitigate False Positives**: Quantum-based approaches address imbalanced datasets, reducing false alarms and providing financial institutions with a more robust tool for fraud detection.

3. **Ensemble Learning**: The stacking ensemble method, combining QSVC as the base classifier and Support Vector Classifier (SVC) as the meta-classifier, further enhances classification performance.

#### 95+% Accuracy Obtained

Our method achieves a remarkable accuracy of 96% on the [Kaggle dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), with a primary focus on maximizing recall for fraudulent transactions.

### Dependencies

- [Qiskit](https://qiskit.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

### Instructions

1. Install the required dependencies using the following command:
   ```bash
   pip install qiskit numpy pandas matplotlib
   ```

2. Open and run the [QuantumFraudDetectiononCreditCardData.ipynb](QuantumFraudDetectiononCreditCardData.ipynb) notebook in a Jupyter environment.

3. Follow the instructions within the notebook to execute the quantum fraud detection algorithm on the provided credit card transaction dataset.

## Stock Fraud Detection

### Purpose

Similar to credit card fraud detection, the goal is to apply quantum machine learning to enhance the detection of fraudulent activities in stock trading.

### Method and Results

#### Dataset and Data Preprocessing

The stock trading dataset, sourced from [Kaggle Dataset](https://www.kaggle.com/datasets/neeoon/flcs-stock-market-transaction-2021-2022?select=flc_2013_2022_notime.csv), is processed using quantum algorithms, offering advantages such as increased resilience to adversarial attacks and improved feature selection.

1. **Improved Accuracy and Efficiency**: Quantum machine learning methodologies significantly improve the accuracy and efficiency of fraud detection in stock trading.

2. **Wide Applicability**: While demonstrated on a stock trading dataset, the techniques are equally relevant to various financial fraud detection scenarios.

### Dependencies

- [Qiskit](https://qiskit.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
### Instructions

1. Install the required dependencies using the following command:
   ```bash
   pip install qiskit numpy pandas matplotlib
   ```

2. Open and run the [QuantumFraudDetectiononStocks.ipynb](QuantumFraudDetectiononStocks.ipynb) notebook in a Jupyter environment.

3. Follow the instructions within the notebook to execute the quantum fraud detection algorithm on the provided stock trading dataset.  

