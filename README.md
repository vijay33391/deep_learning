# Deep Learning: Learning & Implementation - Customer Churn Prediction

This repository contains my learning and hands-on implementation of deep learning concepts applied to a real-world business problem — **Customer Churn Prediction**.

---

## 🎯 Project Objective

- Apply deep learning algorithms to predict whether a customer is likely to churn or stay with the company.
- Learn practical steps in building neural networks using TensorFlow and Keras.

---

## 📖 Learning Goals

During this project, I focused on:

- Understanding the architecture of neural networks.
- Learning about activation functions, loss functions, optimizers.
- Training, validating, and evaluating deep learning models.
- Handling overfitting using regularization techniques.
- Performing hyperparameter tuning to improve model performance.

---

## 📊 Problem Statement

Churn prediction is a classic binary classification problem where the goal is to predict whether a customer will cancel (churn) or continue their subscription based on their profile and service usage data.

---

## 📂 Dataset Description

The dataset contains features such as:

- Customer demographics (Gender, SeniorCitizen, Partner, Dependents)
- Account information (Tenure, Contract, PaymentMethod)
- Service usage (PhoneService, InternetService, StreamingTV, etc.)
- Monthly charges and total charges
- Target variable: `Churn` (Yes/No)

---

## ⚙️ Deep Learning Workflow

### 1️⃣ Data Preprocessing
- Handled missing values.
- Encoded categorical variables using One-Hot Encoding & Label Encoding.
- Scaled numerical features using MinMaxScaler.
- Split data into training and testing sets.

### 2️⃣ Model Architecture
- Input layer: Number of neurons equals number of features.
- Hidden layers: Multiple Dense layers with ReLU activation.
- Output layer: Sigmoid activation function (binary classification).
- Loss Function: Binary Crossentropy
- Optimizer: Adam

### 3️⃣ Model Training
- Trained the neural network with validation splits.
- Applied callbacks for EarlyStopping to prevent overfitting.
- Visualized loss and accuracy curves.

### 4️⃣ Model Evaluation
- Evaluated model using:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix
  - ROC-AUC score

---

## 🏆 Key Results

- Achieved good predictive performance on unseen test data.
- Able to interpret model behavior and business insights from the results.

---

## 🖥️ Technologies Used

- Python 3.x
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run This Project

1️⃣ Clone the repository:

```bash
git clone https://github.com/yourusername/deep-learning-churn.git
cd deep-learning-churn
