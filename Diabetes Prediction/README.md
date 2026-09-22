# Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict whether a patient is likely to have diabetes based on diagnostic and medical measurements.

The project covers data exploration, data cleaning, feature preparation, model training, and model evaluation using **Logistic Regression**.

## 🎯 Objective

The main objective of this project is to build a basic Machine Learning classification model that can predict the diabetes outcome based on the available patient measurements.

## 📊 Dataset

The dataset contains medical and diagnostic measurements used for diabetes prediction.

### Features

* **Pregnancies**
* **Glucose**
* **BloodPressure**
* **SkinThickness**
* **Insulin**
* **BMI**
* **DiabetesPedigreeFunction**
* **Age**

### Target Variable

**Outcome**

* `0` → No Diabetes
* `1` → Diabetes

## 🔍 Project Workflow

The project follows these steps:

1. Import Required Libraries
2. Load the Dataset
3. Understand the Dataset
4. Exploratory Data Analysis
5. Handle Invalid/Missing Values
6. Prepare Features and Target
7. Train-Test Split
8. Feature Scaling
9. Train Logistic Regression Model
10. Model Prediction and Evaluation
11. Conclusion

## 🧹 Data Cleaning

Some medical measurements contain `0` values that are not meaningful for variables such as:

* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI

These values are treated as missing values.

* **Mean** is used for Glucose and BloodPressure.
* **Median** is used for SkinThickness, Insulin, and BMI.

## 📈 Exploratory Data Analysis

The project includes:

* Dataset information
* Column and shape analysis
* Statistical summary
* Missing-value checking
* Invalid zero-value checking
* Outcome distribution
* Correlation heatmap

## 🤖 Machine Learning Model

### Logistic Regression

**Logistic Regression** is used as the classification algorithm to predict whether the patient belongs to the diabetes or non-diabetes class.

Before training the model:

* The dataset is divided into training and testing sets.
* `80%` data is used for training.
* `20%` data is used for testing.
* Feature scaling is performed using `StandardScaler`.

## 📊 Model Evaluation

The model performance is evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
Diabetes-Prediction/
│
├── images/
├── Diabetes_Prediction.ipynb
├── diabetes.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 How to Run

### 1. Clone the Repository

Download or clone the repository to your local system.

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Open:

```text
Diabetes_Prediction.ipynb
```

using Jupyter Notebook or VS Code.

### 4. Run the Notebook

Run the cells step by step to perform data analysis, preprocessing, model training, and evaluation.

## ✅ Conclusion

The project demonstrates a basic Machine Learning approach for diabetes prediction.

The dataset is explored and cleaned, invalid values are handled, features are scaled, and a Logistic Regression model is trained to predict the `Outcome` variable.

Model performance is evaluated using accuracy, classification report, and confusion matrix.

> **Note:** This project is created for educational purposes and should not be used as a medical diagnosis system.

## 👩‍💻 Author

**Neha Chouhan**

B.Tech – Artificial Intelligence

