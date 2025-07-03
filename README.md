# ❤️ Heart Disease Prediction using Python and Logistic Regression

## 📊 Overview

This project implements a **Heart Disease Prediction System** using **Logistic Regression** in Python.  
The model is trained on a publicly available dataset from **Kaggle**, containing patient health metrics to predict whether a person is at risk of heart disease.

The project covers:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model building and evaluation
- Prediction using Logistic Regression.

---

## 📂 Dataset 
- **Features:**
  - `age`: Age of the patient
  - `sex`: Gender (1 = male; 0 = female)
  - `cp`: Chest pain type (4 types)
  - `trestbps`: Resting blood pressure (mm Hg)
  - `chol`: Serum cholesterol (mg/dl)
  - `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
  - `restecg`: Resting electrocardiographic results (values 0,1,2)
  - `thalach`: Maximum heart rate achieved
  - `exang`: Exercise-induced angina (1 = yes; 0 = no)
  - `oldpeak`: ST depression induced by exercise relative to rest
  - `slope`: The slope of the peak exercise ST segment
  - `ca`: Number of major vessels (0-3) colored by fluoroscopy
  - `thal`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
  - `target`: 1 = Heart disease present, 0 = No heart disease

---

## 🛠️ Libraries Used

- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked for missing values
* Visualized feature distributions
* Analyzed correlations between features
* Observed class imbalance in the target variable

---

## 🤖 Model Building

* **Algorithm Used:** Logistic Regression (from Scikit-learn)
* Performed train-test split (80-20)
* Applied model training and prediction
* Evaluated using accuracy score, confusion matrix, and classification report.

---

## ✅ Results

The **Logistic Regression** model achieved an accuracy of approximately **85-90%** depending on the data split.

---

## 📈 Example Output

```text
Accuracy Score: 87%
```

---

## 🔮 Future Work

* Try other classifiers like Random Forest, SVM, and XGBoost.
* Deploy the model using Flask/Django for web usage.
* Improve data preprocessing and hyperparameter tuning.

---


