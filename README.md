# 🚀 Customer Churn Prediction Using ANN

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ann-classification-churn2025.streamlit.app/)  
[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15.0-orange)](https://www.tensorflow.org/)  
---

## 🔹 Project Overview

This project implements an **Artificial Neural Network (ANN)** to predict **customer churn** for a bank. The model evaluates customer data and predicts the probability of a customer leaving.  

The live Streamlit app allows users to **input customer details** and receive real-time churn probability predictions.

 ## Live App
[Customer Churn Prediction](https://ann-classification-churn2025.streamlit.app/)
---

## 🔹 Features

- Interactive **Streamlit interface** for real-time predictions.
- Calculates **churn probability** and provides actionable insights.
- Handles **categorical variables** via **one-hot encoding** and **label encoding**.
- Automatically **scales numerical features** for better ANN performance.
- User-friendly input for testing different customer profiles.

---

## 🔹 Input Features

| Feature | Description |
|---------|-------------|
| CreditScore | Customer's credit score |
| Geography | Customer's country |
| Gender | Male/Female |
| Age | Age of the customer |
| Tenure | Number of years as a customer |
| Balance | Account balance in the bank |
| NumOfProducts | Number of bank products subscribed |
| HasCrCard | Whether customer has a credit card (0/1) |
| IsActiveMember | Whether the customer is an active member (0/1) |
| EstimatedSalary | Estimated annual salary |

---

## 🔹 Model Architecture

- **Input Layer:** 11 features (after encoding)
- **Hidden Layers:** 2 layers with ReLU activation
- **Output Layer:** 1 neuron with Sigmoid activation (churn probability)
- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy

---

## 🔹 Technologies Used

- Python 3.10  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas & NumPy  
- Streamlit  

---
```
## Author
Md Tahmeed
Email: mdtahmeed2003@gmail.com
