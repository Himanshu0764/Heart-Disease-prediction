# ❤️🩺 Heart Disease Prediction System

A Machine Learning project designed to predict the risk of heart disease in patients based on various medical parameters.

**Developed by:** Himanshu Dhaker  
*(Final Year B.E. in Artificial Intelligence & Data Science, MBM University)* **Location:** Jodhpur, Rajasthan

---

## 📑 Table of Contents
- [📌 Project Overview](#-project-overview)
- [📂 File Structure](#-file-structure)
- [🛠️ Technologies & Libraries Used](#️-technologies--libraries-used)
- [📊 Dataset Features](#-dataset-features)
- [📈 Key Workflow](#-key-workflow)
- [🚀 How to Use](#-how-to-use)

---

## 📌 Project Overview
This project leverages Machine Learning to classify whether a patient is at high risk of heart disease or is healthy. It utilizes the **Logistic Regression** algorithm, making it an efficient and interpretable model for medical diagnostics. This module is part of a broader vision for a **Multi-Disease Prediction System**.

## 📂 File Structure
- `heart_disease.ipynb`: The primary Jupyter Notebook containing the end-to-end pipeline: Exploratory Data Analysis (EDA), Model Training, Evaluation, and the Predictive System.
- `heart.csv`: The dataset containing medical records (Age, Cholesterol, Heart Rate, etc.) for over 300 patients.

## 🛠️ Technologies & Libraries Used
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `seaborn`, `matplotlib`
- **Machine Learning:** `scikit-learn`
  - *Modules:* `LogisticRegression`, `StandardScaler`, `train_test_split`, `metrics`

## 📊 Dataset Features
The model is trained on the following medical metrics:
- **Demographics:** Age, Sex
- **Pain & Symptoms:** Chest pain type (cp), Exercise-induced angina (exang)
- **Clinical Measurements:** Resting blood pressure (trestbps), Cholesterol (chol), Fasting blood sugar (fbs), Maximum heart rate (thalach)
- **Advanced Diagnostics:** Resting ECG (restecg), ST depression (oldpeak), Slope, Number of major vessels (ca), Thalassemia (thal)
- **Target:** `0` (High Risk/Disease), `1` (Healthy/Safe)

## 📈 Key Workflow
1. **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations to understand heart disease triggers.
2. **Data Preprocessing:** Feature scaling using `StandardScaler` to ensure the model converges efficiently.
3. **Model Training:** Implementing `LogisticRegression` with optimized parameters.
4. **Feature Importance:** Analyzing which medical factors (like `cp` or `thal`) have the most impact on the diagnosis.
5. **Model Evaluation:** Achieving high accuracy with a detailed view via Confusion Matrix and Classification Reports (Precision, Recall, F1-Score).
6. **Predictive System:** A dedicated code block that takes raw patient data and outputs a "Diagnosis Report" with the probability of disease.

---

### 🚀 How to Use
1. Ensure you have Python installed with `pandas`, `seaborn`, and `sklearn`.
2. Download `heart_disease.ipynb` and `heart.csv` into the same directory.
3. Run the notebook cells sequentially.
4. Use the **Predictive System** section to test with custom input values.
