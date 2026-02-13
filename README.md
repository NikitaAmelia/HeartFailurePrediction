# Heart Failure Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting **heart failure events** using machine learning techniques based on clinical patient data. The notebook implements a complete data science workflow, including data exploration, preprocessing, feature engineering, model training, and evaluation.

The goal of this project is to build predictive models that can help identify patients at higher risk of heart failure, which can support early intervention and decision-making in healthcare analytics.

---

## 🧰 Technologies & Libraries

This project uses the following Python libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Make sure all dependencies are installed before running the notebook.

---

## 🔍 Project Workflow

### 1️⃣ Import Libraries

All required libraries for data manipulation, visualization, and machine learning are imported at the beginning of the notebook.

---

### 2️⃣ Data Loading & Understanding

* Load the heart failure clinical dataset
* Inspect dataset structure, feature types, and basic statistics
* Check for missing values and data quality issues

---

### 3️⃣ Exploratory Data Analysis (EDA)

* Distribution analysis of numerical features
* Visualization of relationships between features and the target variable (heart failure event)
* Correlation analysis to identify important predictors

---

### 4️⃣ Data Preprocessing

* Handle missing values (if any)
* Encode categorical features
* Scale numerical features where necessary

---

### 5️⃣ Feature Selection

Relevant features are selected based on statistical analysis and correlation with the target variable to improve model performance.

---

### 6️⃣ Model Building

Several machine learning models are trained and evaluated, such as:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

These models are compared to determine the best-performing approach.

---

### 7️⃣ Model Evaluation

Models are evaluated using common classification metrics:

* Accuracy
* Precision
* Recall
* F1-score

Evaluation results help identify the most reliable model for predicting heart failure events.

---

## ▶️ How to Run the Project

1. Ensure Python version ≥ 3.8
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:

   ```bash
   jupyter notebook HeartFailure.ipynb
   ```
4. Run all cells sequentially

---

## 🎯 Conclusion

This project demonstrates how machine learning can be applied to healthcare data to predict heart failure events. Through proper data preprocessing, feature selection, and model evaluation, the project highlights the potential of data-driven approaches in supporting medical decision-making.

---

## 👩‍💻 Author

Nikita Amelia Valencia  
Machine Learning & Data Science Enthusiast

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only** and should not be used as a substitute for professional medical advice or diagnosis.
