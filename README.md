# Artificial Neural Networks with PyTorch

This repository contains my first practical work in **Deep Learning**, where I implemented Artificial Neural Networks (ANNs) for both **Classification** and **Regression** using **PyTorch**.

The main goal of this work was to understand the basic workflow of building, training, and evaluating neural network models.

## Topics Covered

* Artificial Neural Networks (ANN)
* Classification using ANN
* Regression using ANN
* Data preprocessing
* Feature scaling
* Tensor conversion using PyTorch
* Dataset and DataLoader
* Forward propagation
* Loss functions
* Backpropagation
* Adam optimizer
* ReLU activation function
* Model evaluation

## Projects

### 1. ANN for Classification

A neural network was implemented for a multi-class classification problem using the **Date Fruit dataset**.

**Dataset details:**

* Samples: 898
* Input features: 34
* Classes: 7
* Framework: PyTorch

The workflow included:

1. Loading and preprocessing the dataset
2. Encoding the target classes
3. Splitting the dataset into training and testing sets
4. Feature scaling
5. Converting the data into PyTorch tensors
6. Creating DataLoaders
7. Building the ANN model
8. Training the model using backpropagation
9. Evaluating the model on test data

**Model components:**

* Input layer
* Hidden layers
* ReLU activation
* Output layer
* Cross Entropy Loss
* Adam optimizer

**Test Result:**

The model correctly classified **172 out of 180 test samples**, giving approximately **95.6% test accuracy**.

---

### 2. ANN for Regression

A neural network was implemented for a regression problem using the **Combined Cycle Power Plant dataset**.

**Dataset details:**

* Samples: 9,568
* Input features: 4
* Framework: PyTorch

The workflow included:

1. Loading the dataset
2. Separating input features and target values
3. Feature scaling
4. Splitting the data into training and testing sets
5. Converting the data into PyTorch tensors
6. Creating DataLoaders
7. Building the ANN model
8. Training the model
9. Evaluating regression performance

**Model components:**

* Input layer
* Hidden layers
* ReLU activation
* Output layer
* Mean Squared Error Loss
* Adam optimizer

**Test Results:**

* **Test MSE:** 18.84
* **R² Score:** 0.934

## Technologies Used

* Python
* PyTorch
* NumPy
* pandas
* scikit-learn
* Matplotlib

## ANN Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature Scaling
   ↓
Train/Test Split
   ↓
PyTorch Tensors
   ↓
DataLoader
   ↓
ANN Model
   ↓
Forward Propagation
   ↓
Loss Calculation
   ↓
Backpropagation
   ↓
Adam Optimizer
   ↓
Model Evaluation
```

## Repository Structure

```text
Artificial-Neural-Networks/
│
├── ANN_Classifier.ipynb
├── ANN_Regression.ipynb
├── README.md
```

## What I Learned

Through these implementations, I gained practical understanding of how neural networks are used for two different types of problems.

For classification, I learned how an ANN predicts classes using an output layer and classification loss.

For regression, I learned how an ANN predicts continuous numerical values and how metrics such as **MSE** and **R²** are used for evaluation.

This work is part of my ongoing journey of learning **Deep Learning and Artificial Intelligence**.

---

If you find this repository useful, feel free to explore the notebooks and code.
