# Breast Cancer Classification using Machine Learning

This project uses a Logistic Regression model to classify breast cancer tumors as either malignant (cancerous) or benign (non-cancerous) based on diagnostic features.

---

## 📋 Project Overview

* **Model:** Logistic Regression
* **Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset from Scikit-learn (`sklearn.datasets.load_breast_cancer()`).
* **Features:** 30 numeric features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
* **Target:** `0` (Malignant) or `1` (Benign).

---

## 🚀 Model Performance

The model was trained on 80% of the data and tested on the remaining 20%. To improve performance and prevent convergence warnings, the features were standardized using `StandardScaler`.

* **Training Accuracy:** 94.9%
* **Testing Accuracy:** 93.0%

---

## 🛠️ How to Run This Project

You can clone this repository and run the Jupyter Notebook on your local machine.

**1. Clone the repository:**
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
