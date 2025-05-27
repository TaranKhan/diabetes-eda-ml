# 🩺 Diabetes Prediction using EDA & ML

This project performs Exploratory Data Analysis (EDA) and builds machine learning models to predict diabetes outcomes using the PIMA Indian Diabetes dataset.

---

## 📊 What This Project Includes

- Data cleaning (handling zero values in health indicators)
- Univariate visualizations and correlation heatmap
- ML models: Logistic Regression and Random Forest
- Evaluation using confusion matrices, classification reports, accuracy, precision, recall, F1-score
- Feature importance comparison across models

---

## 📁 Dataset
- [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## 🧪 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🧠 Key Insights
- **Glucose**, **BMI**, and **Age** were the top predictors of diabetes
- Logistic Regression had **higher recall**, making it more suitable for minimizing false negatives in a healthcare context
- Feature importance and confusion matrices helped compare model behavior

---

## 🧰 How to Run This Project

```bash
pip install -r requirements.txt
jupyter notebook Diabetes_EDA_ML_Project.ipynb
