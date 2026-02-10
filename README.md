# task8
# Model Comparison & Best Model Selection

## 📌 Objective
The goal of this project is to compare multiple machine learning classification models
and select the best performing model based on evaluation metrics such as
Accuracy, Precision, Recall, and F1-score.

---

## 📊 Dataset
- **Dataset Used:** Breast Cancer Dataset
- **Source:** sklearn.datasets
- **Problem Type:** Binary Classification (Malignant / Benign)

---

## ⚙️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib

---

## 🧠 Models Trained
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 🔄 Workflow
1. Loaded the Breast Cancer dataset
2. Performed train-test split
3. Applied feature scaling
4. Trained multiple ML models
5. Evaluated models using Accuracy, Precision, Recall, and F1-score
6. Compared model performance using a bar chart
7. Selected the best model based on F1-score
8. Saved the best performing model

---

## 📈 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

F1-score was given priority because it balances precision and recall and is
more reliable for classification problems.

---

## 🏆 Best Model Selected
- **Random Forest Classifier**
- Reason: Highest F1-score and better generalization on test data

---

## 💾 Saved Model
The best performing model is saved as:
