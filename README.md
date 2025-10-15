#Neuro-Glyph Analytics: Diabetes Prediction using an Artificial Neural Network

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Neural Network](https://img.shields.io/badge/Neural_Network-8A2BE2-blueviolet)](https://en.wikipedia.org/wiki/Neural_network)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?logo=Keras&logoColor=white)](https://keras.io/)

**DiabeNet** is a deep learning project that predicts the likelihood of an individual having diabetes based on key health metrics. It utilizes an Artificial Neural Network (ANN) built with TensorFlow and Keras to classify patients from the PIMA Indians Diabetes Dataset.

This repository includes the full Python script for data preprocessing, model training, evaluation, a detailed data profile report (`DiabeNet_Predictor_Report.html`), and the dataset itself (`diabetes.csv`).

---

## 📋 Table of Contents
- [About The Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Key Features](#key-features)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Model Performance](#model-performance)

---

## 📖 About The Project

The goal of this project is to build an accurate and efficient classifier for diabetes prediction. Early diagnosis is crucial for managing diabetes, and machine learning models can serve as a valuable tool for medical professionals.

This project implements a sequential Artificial Neural Network to learn patterns from historical patient data and make predictions on new, unseen data. The process involves:
1.  Loading and performing an exploratory data analysis (EDA) on the dataset.
2.  Preprocessing the data by splitting it into training/testing sets and applying feature scaling.
3.  Building, compiling, and training a Keras Sequential model.
4.  Evaluating the model's performance using key metrics like accuracy, confusion matrix, and a classification report.

---

## 🛠️ Tech Stack

- **Python**: Core programming language
- **TensorFlow & Keras**: For building and training the neural network
- **Pandas**: For data manipulation and loading the CSV file
- **Scikit-learn**: For data splitting, feature scaling, and performance metrics
- **Matplotlib & Seaborn**: For creating visualizations like the confusion matrix
- **Pandas Profiling**: Used to generate the detailed `DiabeNet_Predictor_Report.html`

---

## ✨ Key Features

- **Deep Learning Model**: A robust ANN with multiple dense layers for effective pattern recognition.
- **Data Preprocessing Pipeline**: Implements `StandardScaler` to normalize features for optimal model performance.
- **Comprehensive Evaluation**: Generates an accuracy score, a detailed classification report (with precision, recall, F1-score), and a confusion matrix heatmap.
- **Full EDA Report**: Includes a complete data profile report for in-depth dataset analysis.

---

## 📊 Dataset

The project uses the **PIMA Indians Diabetes Dataset**. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains the following features:

- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index
- `DiabetesPedigreeFunction`: A function that scores likelihood of diabetes based on family history
- `Age`: Age in years
- `Outcome`: The target variable (0 for non-diabetic, 1 for diabetic)

---

## 🚀 Getting Started

Follow these steps to get a local copy up and running.

### **Prerequisites**
- Python 3.8 or higher
- pip (Python package installer)

### **Installation**

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/Ayush-Shrivas/Neuro-Glyph-Analytics.git](https://github.com/Ayush-Shrivas/Neuro-Glyph-Analytics.git)
    ```
2.  **Navigate to the project directory**
    ```sh
    cd Neuro-Glyph-Analytics
    ```
3.  **Create and activate a virtual environment** (recommended)
    ```sh
    # For Windows
    python -m venv venv
    .\venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```
4.  **Install the required dependencies**
    ```sh
    pip install tensorflow pandas scikit-learn matplotlib seaborn
    ```

---

## 🏃 Usage

To run the complete pipeline (data loading, training, and evaluation), execute the main Python script:

```sh
python artificial_neural_network_diabetes_dataset_.py
```
---
# 📧 Contact


**Ayush Shrivas**

-   **GitHub**: [@Ayush-Shrivas](https://github.com/Ayush-Shrivas)
-   **LinkedIn**: [Ayush Shrivas](https://www.linkedin.com/in/ayush-shrivas-190475299/)
