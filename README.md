# Elevate_Lab16

# Hyperparameter Tuning using GridSearchCV — Internship Task 16

## 📌 Project Title

Hyperparameter Tuning and Model Optimization using GridSearchCV (Scikit-learn)

---

## 🎯 Objective

The objective of this task is to perform hyperparameter tuning on machine learning models using GridSearchCV and improve model performance through systematic parameter optimization and cross-validation.

---

## 🧠 Concepts Covered

* Hyperparameters vs Parameters
* GridSearchCV
* Cross-Validation
* Model Optimization
* Pipeline usage
* Performance Comparison

---

## 📂 Dataset Used

**Breast Cancer Dataset** from Scikit-learn built-in datasets.

* Binary classification problem
* Features: 30 numerical medical measurements
* Target: Malignant / Benign

---

## 🛠 Tools & Libraries

* Python
* Scikit-learn
* Pandas
* Matplotlib
* Seaborn
* Joblib
* Google Colab

---

## 🔬 Models Used

Two models were trained and tuned:

1. Support Vector Machine (SVM)
2. Random Forest Classifier

Both models were evaluated with:

* Default parameters
* Tuned parameters using GridSearchCV

---

## ⚙️ Methodology

1. Loaded the dataset from sklearn
2. Converted it into a pandas DataFrame
3. Performed train-test split with stratification
4. Built ML pipelines (with scaling for SVM)
5. Trained default models for baseline accuracy
6. Defined hyperparameter grids
7. Applied GridSearchCV with 5-fold cross-validation
8. Extracted best parameters
9. Evaluated tuned models on test set
10. Compared default vs tuned performance
11. Saved all outputs automatically

---

## 🔍 Hyperparameters Tuned

### SVM

* C
* Kernel
* Gamma

### Random Forest

* Number of estimators
* Max depth
* Min samples split

---

## 📊 Outputs Generated (Auto-Saved)

The notebook automatically saves:

* ✅ Best parameter JSON files
* ✅ Performance comparison CSV
* ✅ Confusion matrix images
* ✅ Classification reports (TXT)
* ✅ Tuned model files (.pkl)
* ✅ Final report file
* ✅ README file

No screenshots required — everything is programmatically stored.

---

## 📈 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision / Recall / F1 Score
* Cross-validation score (inside GridSearchCV)

---

## 🧪 Unique Approach Used

Instead of tuning only one model, this project:

* Tunes **two different models**
* Uses **pipelines**
* Performs **side-by-side comparison**
* Automatically **saves every artifact**
* Automatically **generates report files**
* Submission ready without manual screenshots

---

## 🚀 How to Run

Open the notebook in Google Colab and run all cells in order:

1. Install libraries
2. Load dataset
3. Split data
4. Train default models
5. Run GridSearchCV
6. Evaluate results
7. Download outputs ZIP
8. Push to GitHub

---

## ❗ Key Learning Outcomes

* Understood hyperparameter tuning
* Learned GridSearchCV workflow
* Used cross-validation correctly
* Avoided tuning on test data
* Built reproducible ML pipeline
* Automated result saving

---

## 📬 Submission Contents

This repository contains:

* Colab Notebook (.ipynb)
* Outputs folder
* Best parameter files
* Saved models
* Performance tables
* Confusion matrix plots
* REPORT.md
* README.md

---

## ✅ Conclusion

Hyperparameter tuning using GridSearchCV significantly improves model performance compared to default settings. Cross-validation ensures reliable parameter selection and prevents overfitting. This task demonstrates practical model optimization workflow used in real ML projects.

---
