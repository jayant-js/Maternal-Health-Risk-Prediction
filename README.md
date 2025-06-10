# Maternal Health Risk Analysis

## 📄 Overview
This project analyzes maternal health risk levels using machine learning classification techniques. The dataset contains 1013 instances with 7 key features related to maternal health. The goal is to classify risk levels into three categories: **low, mid, and high**.

## 📊 Dataset Information
The dataset used in this project is sourced from the UCI Machine Learning Repository:  
[Maternal Health Risk Dataset](https://archive.ics.uci.edu/dataset/863/maternal+health+risk)

### Features:
1. **Age** - Age of the patient
2. **SystolicBP** - Systolic blood pressure
3. **DiastolicBP** - Diastolic blood pressure
4. **BS (Blood Sugar)** - Blood glucose level
5. **BodyTemp** - Body temperature
6. **HeartRate** - Heart rate of the patient
7. **RiskLevel** - Target variable (Low, Mid, High)

## 📌 Project Structure
- **Exploratory Data Analysis (EDA)** - Data distribution, feature analysis, and insights.
- **Data Preprocessing** - Handling missing values, outlier removal, and feature scaling.
- **Model Training** - Applying machine learning models for classification.
- **Evaluation & Visualization** - Confusion matrix, recall metrics, accuracy metrics and final model insights.

## 🔧 Technologies Used
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- Jupyter Notebook
- LaTeX for report generation
- Overleaf for document formatting

## 📈 Results & Insights

- Multiple classification models were evaluated using both **accuracy** and **recall** metrics.
- Given the medical context, **recall** was prioritized to minimize false negatives and ensure high sensitivity in detecting maternal health risks.
- Key features contributing to maternal health risk levels were identified and analyzed for their impact.
- The final selected model demonstrated strong recall performance, making it a reliable and safe choice for predicting maternal risk levels.

## 📂 Files Included
- **Maternal_Health_Risk.pdf** - Detailed report with analysis, methodology, and findings.
- **Jupyter Notebook** - Python scripts for data preprocessing, model training, and evaluation.
