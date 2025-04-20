# 🧪 COVID-19 State-wise Severity Classification in India using Machine Learning

This repository contains two machine learning mini-projects focused on analyzing and classifying COVID-19 severity across Indian states and union territories. It explores classification models to predict either the **discharge recovery rate** or the **active case severity level** using various supervised learning algorithms.

---

## 📌 Objectives

### 📁 Notebook 1: Discharge Ratio Classification

- **Goal**: Classify states into **High Recovery (1)** and **Low Recovery (0)** categories based on **Discharge Ratio**.
- **Models Used**:
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Decision Tree

### 📁 Notebook 2: Active Case Severity Classification

- **Goal**: Classify states into **Low**, **Medium**, or **High** severity based on **Active Case Ratio**.
- **Models Used**:
  - Naive Bayes
  - K-Nearest Neighbors (KNN, k=5)

---

## 📊 Dataset Overview

- **File**: `Latest Covid-19 India Status.csv`
- **Observations**: 36 (States/UTs)
- **Features**:
  - Total Cases
  - Active
  - Discharged
  - Deaths
  - Active Ratio
  - Discharge Ratio
  - Death Ratio
  - Population
- **Target Variables**:
  - `Discharge Ratio` (Binary classification)
  - `Severity` derived from `Active Ratio` (Multi-class classification)

---

## 🔁 Workflow

1. **Data Import**
2. **Exploratory Data Analysis**
3. **Missing & Duplicate Data Handling**
4. **Feature Engineering**
5. **Label Encoding of Target Variables**
6. **Normalization using MinMaxScaler**
7. **Model Training & Prediction**
8. **Performance Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

---

## 📂 Folder Structure


