# AI-Based-Neurodegenerative-Disease-Detection-using-CSF-Biomarkers
This project demonstrates how AI can assist in early detection of neurodegenerative diseases, potentially improving diagnosis accuracy and reducing dependency on expensive imaging techniques.
# 🧠 AI-Based Neurodegenerative Disease Detection using CSF Biomarkers

## 📌 Overview

This project presents an end to end AI driven framework for detecting neurodegenerative diseases such as Alzheimer’s Disease (AD) and Parkinson’s Disease (PD) using cerebrospinal fluid (CSF) biomarkers and clinical assessment data.

Traditional diagnostic methods rely on expensive imaging techniques and often detect diseases at advanced stages. This project aims to enable early and accurate detection using machine learning by analyzing biological and clinical patterns.

---

## 🎯 Objectives

* Develop a multiclass classification system for neurodegenerative diseases
* Utilize CSF biomarkers and clinical data for early detection
* Improve diagnostic accuracy using ensemble machine learning techniques
* Reduce dependency on costly imaging-based diagnosis

---

## 🛠️ Tech Stack

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn
* **ML Models:** Random Forest, XGBoost, CatBoost
* **Techniques:** Stacking Ensemble, SMOTE, Feature Engineering
* **Visualization:** Matplotlib, Seaborn

---

## 📊 Dataset

This project uses publicly available biomedical datasets:

* **ADNI (Alzheimer’s Disease Neuroimaging Initiative)**
* **PPMI (Parkinson’s Progression Markers Initiative)**

These datasets include:

* CSF biomarker measurements
* Clinical assessment scores


---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handling missing values using **MICE** and **KNN Imputation**
* Outlier treatment using clipping techniques
* Data normalization and standardization

### 2. Feature Engineering

* Creation of biomarker ratios
* Selection of significant clinical and biological features

### 3. Handling Class Imbalance

* Applied **SMOTE-Tomek** technique to balance dataset

### 4. Model Development

* Base Models:

  * Random Forest
  * XGBoost
  * CatBoost
* Final Model:

  * **Stacking Ensemble (with Logistic Regression as meta-learner)**

### 5. Model Evaluation

* Accuracy
* Precision
* Recall
* F1-score
* Balanced Accuracy

---

## 📈 Results

| Dataset | Accuracy | Balanced Accuracy | F1 Score |
| ------- | -------- | ----------------- | -------- |
| ADNI    | 93.48%   | 92.99%            | 0.93     |
| PPMI    | 86.12%   | 81.56%            | 0.82     |

### Key Observations:

* High accuracy in detecting Alzheimer’s and Parkinson’s disease
* Slightly lower performance for early-stage conditions (MCI, Prodromal)
* Ensemble model significantly improved prediction performance

---

## 🔍 Key Insights

* Combining CSF biomarkers with clinical data improves diagnostic accuracy
* Ensemble learning captures complex patterns better than individual models
* CSF biomarkers are strong indicators of neurodegenerative changes

---


## 💡 Business / Research Impact

* Enables early detection of neurodegenerative diseases
* Reduces reliance on expensive imaging techniques
* Supports clinical decision-making using AI
* Provides a scalable framework for biomedical AI systems

---

## 🚀 Future Improvements

* Integrate neuroimaging data (MRI, PET scans)
* Include genetic and longitudinal patient data
* Improve detection of early stage disease conditions
* Deploy as a web-based diagnostic tool



