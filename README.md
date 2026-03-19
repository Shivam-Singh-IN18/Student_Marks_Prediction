# 📊 Student Performance Prediction using XGBoost

## 🚀 Overview

This project focuses on predicting students' final exam scores using machine learning techniques.
By analyzing academic behavior and socio-environmental factors, the model helps identify performance trends and supports data-driven decision-making in education.

---

## 🎯 Problem Statement

Traditional methods fail to accurately identify students at risk of poor performance.
This project builds a predictive system that estimates student marks using multiple features, enabling early intervention and improved academic outcomes.

---

## 🧠 Approach

The project follows a complete **machine learning pipeline**:

* Data preprocessing & cleaning
* Feature engineering
* Encoding categorical variables
* Scaling numerical features
* Model building using **XGBoost Regressor**
* Evaluation using standard regression metrics

---

## 📂 Dataset

* Source: Kaggle Student Performance Dataset
* Records: 708
* Features: 10

### Key Features:

* Study Hours per Week
* Attendance Rate
* Past Exam Scores
* Parental Education Level
* Internet Access
* Extracurricular Activities

Target Variable: **Final Exam Score**

---

## ⚙️ Tech Stack

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost
* **Concepts:** Regression, Feature Engineering, Pipeline

---

## 🔍 Model Details

* Model: **XGBoost Regressor**
* Train-Test Split: 80:20
* Key Hyperparameters:

  * n_estimators = 200
  * learning_rate = 0.1
  * max_depth = 4

---

## 📈 Results

* 📉 Mean Squared Error (MSE): **10.5**
* 📊 R² Score: **0.75**

The model explains **75% of the variance**, showing strong predictive capability.

---

## 📊 Visualization

* Scatter plot of Actual vs Predicted values
* Predictions closely align with real values, indicating good performance

---

## 💡 Key Insights

* Study hours and past scores are strong indicators of performance
* Attendance plays a critical role
* Socio-economic factors also influence outcomes

---

## ⚠️ Limitations

* Limited dataset diversity
* Model interpretability (XGBoost is a black-box model)
* Possible overfitting on smaller datasets

---

## 🚀 Future Improvements

* Add SHAP for model explainability
* Hyperparameter tuning (Grid Search)
* Cross-validation
* Deploy as a web app

---

## 🧪 Sample Prediction

The model can predict scores for new student data inputs, making it useful for real-time academic analysis systems.

---

## 📌 Conclusion

This project demonstrates how machine learning can effectively predict student performance and support early intervention strategies in education.

---

## 📎 Project Files

* 📄 Full Project Report: 
* 📓 Jupyter Notebook: Included in repository

---
