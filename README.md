# Lab 3: Preprocessing for Prediction – The Cricket Dataset

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/KP-AI-ML-Labs/Lab3-Preprocessing/blob/main/g_Lab3_NewS.ipynb)

---

## 📖 Story Point  
Before we can build any reliable models, we must clean our data. Real-world data is messy—missing values, mixed formats. This lab is our data sanitization phase.  

---

## 🎓 Mapping to Lecture  
- **Lectures:** Data Preprocessing (7, 8, 9)  
- **Python Libraries:** `pandas`, `numpy`, `scikit-learn`  
- **Category:** Data Wrangling & Feature Engineering  

---

## 🧪 In-Class Practical  

**Objective:**  
Apply a full preprocessing pipeline—imputation for missing data, encoding for categorical data, scaling for numerical data—using `ColumnTransformer`.  

**Tasks:**  
1. Load `simulated_dirty_match_data.csv`  
2. Identify numerical & categorical columns  
3. Define a **numerical pipeline**: median imputation + scaling  
4. Define a **categorical pipeline**: one-hot encode venue column  
5. Combine into a **ColumnTransformer**, fit & transform `X`  
6. Inspect final preprocessed feature matrix  

---

## 🏡 Home Task  
Write a few sentences explaining:  
- Why did the transformed data shape change?  
- Which step caused extra columns?  
- Why is one-hot encoding necessary?  

---

## ✅ Deliverable  
A fully preprocessed feature set `X_transformed` using a clean, reusable pipeline.  

---

## ⚙ Requirements  
Install required libraries:  
`!pip install -r requirements.txt ` 
