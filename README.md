# 🤖 AI & ML Basic Models — Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib">
</p>

<p align="center">
  <strong>DevSphere Internship — Week 3</strong>
</p>

<p align="center">
  Basic machine learning implementations using Python and Scikit-learn, covering classification and regression.
</p>

---

## 📌 Overview

This repository contains the practical work completed for **Week 3 of the DevSphere Internship**.

The tasks focus on fundamental supervised machine learning concepts, including:

- Dataset loading
- Data preparation
- Training and testing
- Classification
- Regression
- Model predictions
- Model evaluation
- Data visualization

The implementations are developed using **Python and Scikit-learn** in Google Colab notebooks.

---

## 📂 Repository Structure

```text
ai_ml_basic_models_python/
│
├── ai_basic_ml/
│   └── basic_ml_model.ipynb
│
├── ml_regression/
│   └── basic_regression_model.ipynb
│
└── README.md
```

---

# 🧠 Task 1 — Basic Machine Learning Model

## 📊 Dataset

**Iris Dataset**

The Iris dataset is a classification dataset containing measurements of iris flowers from three different classes.

## 🤖 Model

**Gaussian Naive Bayes**

The model is trained using an 80/20 training and testing split.

## 🔬 Implementation

The notebook includes:

- Loading the Iris dataset
- Separating features and target values
- Splitting the dataset into training and testing sets
- Visualizing class distribution
- Training a Gaussian Naive Bayes model
- Making predictions
- Evaluating model performance
- Displaying a confusion matrix
- Showing sample predictions

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 📋 Results

```text
Dataset: Iris
Total Samples: 150
Training Samples: 120
Testing Samples: 30

Model: Gaussian Naive Bayes
Model Training Completed.

Model Performance
-----------------
Accuracy  : 96.67%
Precision : 96.97%
Recall    : 96.67%
F1 Score  : 96.66%
```

## 🔎 Sample Predictions

```text
1. Actual: setosa | Predicted: setosa
2. Actual: virginica | Predicted: virginica
3. Actual: versicolor | Predicted: versicolor
4. Actual: versicolor | Predicted: versicolor
5. Actual: setosa | Predicted: setosa
```

## 🔄 Workflow

```text
Iris Dataset
     │
     ▼
Data Preparation
     │
     ▼
Train/Test Split
     │
     ▼
Gaussian Naive Bayes
     │
     ▼
Predictions
     │
     ▼
Model Evaluation
```

---

# 📈 Task 2 — Regression Model

## 🏠 Dataset

**California Housing Dataset**

The California Housing dataset contains information about housing districts and their corresponding median house values.

## 🤖 Model

**Linear Regression**

The model is used to predict house values based on selected housing-related parameters.

## 🔬 Features Used

The implementation uses five features:

1. Median Income
2. House Age
3. Average Rooms
4. Latitude
5. Longitude

## 🎯 Target

**Median House Value**

## 🔬 Implementation

The notebook includes:

- Loading the California Housing dataset
- Selecting five relevant features
- Splitting the dataset into training and testing sets
- Training a Linear Regression model
- Making house-value predictions
- Evaluating model performance
- Visualizing actual and predicted values
- Displaying sample predictions

## 📊 Evaluation Metrics

- R² Score
- Mean Squared Error

## 📋 Results

```text
Dataset: California Housing Dataset
Total Samples: 20640
Features: 5
Training Samples: 16512
Testing Samples: 4128

Model: Linear Regression
Model Training Completed.

Model Performance
-----------------
R² Score           : 0.5814
Mean Squared Error : 0.5486
```

## 🔎 Sample Predictions

```text
1. Actual: 0.48 | Predicted: 0.74
2. Actual: 0.46 | Predicted: 1.75
3. Actual: 5.00 | Predicted: 2.47
4. Actual: 2.19 | Predicted: 2.89
5. Actual: 2.78 | Predicted: 2.71
```

## 🔄 Workflow

```text
California Housing Dataset
          │
          ▼
Feature Selection
          │
          ▼
Train/Test Split
          │
          ▼
Linear Regression
          │
          ▼
House Value Predictions
          │
          ▼
Model Evaluation
```

---

# 🛠️ Technologies & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,github,vscode" alt="Technologies">
</p>

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming language |
| 🤖 Scikit-learn | Machine learning models and evaluation |
| 📈 Matplotlib | Data visualization |
| 📓 Google Colab | Notebook development and execution |
| 🔗 GitHub | Project hosting and version control |

---

# 📚 Machine Learning Concepts

## Classification

Classification is used to predict a category or class.

In Task 1:

```text
Iris Features
      ↓
Gaussian Naive Bayes
      ↓
Predicted Iris Class
```

## Regression

Regression is used to predict a continuous numerical value.

In Task 2:

```text
Housing Features
      ↓
Linear Regression
      ↓
Predicted House Value
```

---

# 📊 Model Evaluation

## Classification

The classification model is evaluated using:

- **Accuracy** — measures the overall proportion of correct predictions.
- **Precision** — measures how many predicted positive results are correct.
- **Recall** — measures how many actual positive results are correctly identified.
- **F1 Score** — combines precision and recall.
- **Confusion Matrix** — shows correct and incorrect predictions for each class.

## Regression

The regression model is evaluated using:

- **R² Score** — measures how well the model explains variation in the target.
- **Mean Squared Error** — measures the average squared difference between actual and predicted values.

---

# 📊 Visualizations

The notebooks include visual outputs for both tasks.

### Task 1

- Iris class distribution
- Naive Bayes confusion matrix

### Task 2

- Actual vs Predicted House Values

---

# 🚀 How to Run

The notebooks were developed using **Google Colab**.

1. Open the required `.ipynb` notebook.
2. Open it using Google Colab or Jupyter Notebook.
3. Run the cells in order.
4. Review the generated outputs, metrics, predictions, and visualizations.

The datasets are loaded directly through Scikit-learn.

---

# 🎯 Learning Outcomes

Through these tasks, the following practical concepts were covered:

- Understanding supervised machine learning
- Working with machine learning datasets
- Preparing features and target values
- Splitting data into training and testing sets
- Training classification models
- Training regression models
- Making predictions
- Evaluating model performance
- Creating basic machine learning visualizations
- Working with Google Colab notebooks
- Organizing machine learning work using GitHub

---

# 🏢 Internship

**DevSphere Internship — Week 3**

Practical work focused on fundamental **Artificial Intelligence and Machine Learning** concepts using Python and Scikit-learn.

---

# 👨‍💻 Author

**Abdul Samad**

GitHub: [abdulsamad010](https://github.com/abdulsamad010)
