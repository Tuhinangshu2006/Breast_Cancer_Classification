

---

# 🩺 Breast Cancer Classification using Machine Learning

*A complete end-to-end ML pipeline for predicting Malignant vs Benign tumors*

---

## 📌 Project Overview

This project builds a **machine learning model** to classify breast tumors as **Malignant** or **Benign** using the *Breast Cancer Wisconsin (Diagnostic) Dataset*.
It demonstrates a complete workflow used in real-world machine learning projects, including **data preprocessing, EDA, model development, hyperparameter tuning, and performance evaluation**.

The objective is to develop a reliable diagnostic classifier while showcasing strong machine learning engineering skills.

---

## 📂 Dataset

* **Source:** Breast Cancer Wisconsin Diagnostic Dataset (Kaggle)
* **Target Variable:** `diagnosis`

  * **M** = Malignant
  * **B** = Benign

*Features represent characteristics of cell nuclei extracted from medical images, including:*

* radius, texture, perimeter, area
* compactness, concavity
* symmetry, fractal dimension
* mean, worst, and standard error metrics

---

## 🛠 Technologies & Libraries

* **Python**
* **pandas, numpy** – Data handling
* **matplotlib** – Visualization
* **scikit-learn** – Modeling, pipelines, GridSearchCV

---

## 🚀 Project Workflow

### **1️⃣ Data Preprocessing**

* Cleaned and explored the dataset
* Dropped irrelevant columns
* Encoded target labels
* Standardized numerical features
* Split into training, validation, and test sets

### **2️⃣ Exploratory Data Analysis**

* Checked class balance
* Visualized feature distributions
* Identified correlations
* Highlighted influential features (e.g., radius, perimeter, concavity)

### **3️⃣ Model Development**

Trained and compared multiple algorithms:

* Logistic Regression
* Support Vector Classifier (SVC)
* Random Forest
* Gradient Boosting

### **4️⃣ Hyperparameter Tuning**

Applied **GridSearchCV** to optimize:

* C, gamma, kernel (SVC)
* n_estimators, max_depth (Random Forest)
* learning_rate, n_estimators (Gradient Boosting)
* Regularization strength (Logistic Regression)

### **5️⃣ Model Evaluation**

Evaluated using:

* Accuracy
* Precision, Recall, F1-score
* Confusion Matrix
* ROC-AUC Score

**Best models achieved:**

* **Accuracy:** 97–99%
* **AUC:** above 0.98
* Very low false negatives — crucial because misclassifying a malignant tumor can have severe consequences.

---

## 🧠 Key Insights

* SVC and Gradient Boosting delivered the strongest performance after tuning.
* Features related to radius, perimeter, and concavity were highly predictive.
* Hyperparameter tuning significantly improved model accuracy and generalization.
* The project follows a **professional, industry-standard ML workflow**, demonstrating practical proficiency and strong analytical skills.

---

## 📁 File Structure

```
📦 Breast_Cancer_Classification
 ┣ 📜 Breast_Cancer_Classification.ipynb     (main project notebook)
 ┗ 📜 breast_cancer_data.csv                 (dataset)
```

---

## 🧪 How to Run the Project

Install the required Python libraries:

```
pip install pandas numpy matplotlib scikit-learn
```

Launch the notebook:

```
jupyter notebook Breast_Cancer_Classification.ipynb
```

---

## 🏁 Final Note

This project demonstrates my ability to independently develop a complete machine learning solution—from raw data to a tuned, evaluated, and interpretable model. It highlights my strengths in Python, scikit-learn, statistical analysis, EDA, and model optimization.
The workflow aligns with industry expectations for internships and machine learning roles, making it suitable for technical interviews and portfolio presentation.

---

