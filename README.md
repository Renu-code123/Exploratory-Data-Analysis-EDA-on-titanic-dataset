
# 🚢 EDA on Titanic Dataset - Logistic Regression with Python  

This repository contains an **Exploratory Data Analysis (EDA)** and implementation of **Logistic Regression** on the Titanic dataset to predict passenger survival.  

The Titanic dataset from Kaggle is one of the most well-known beginner datasets in machine learning and serves as a great introduction to classification problems.  

---

## 📌 Repository Description  

- Perform **EDA** to understand passenger demographics and survival distribution.  
- Apply **Logistic Regression** for binary classification (Survived vs Not Survived).  
- Visualize insights using plots (e.g., survival rate by class, age, gender).  
- Provide a baseline machine learning workflow that can be extended to advanced models.  

---

## 🗂 Dataset  

- Source: [Titanic Dataset - Kaggle](https://www.kaggle.com/c/titanic)  
- A **semi-cleaned version** is used in this notebook.  
- If using the raw dataset from Kaggle, you may need additional preprocessing (handling missing values, encoding categorical variables, etc.).  

---

## ⚙️ Tech Stack  

- **Python 3.8+**  
- **Libraries used:**  
  - `pandas` → data manipulation  
  - `numpy` → numerical computations  
  - `matplotlib` & `seaborn` → visualizations  
  - `scikit-learn` → logistic regression & evaluation metrics  

---

## 🔍 Workflow  

1. **Data Exploration (EDA):**  
   - Check dataset info, missing values, and distributions.  
   - Visualize relationships (e.g., class vs survival, age distribution, gender impact).  

2. **Data Preprocessing:**  
   - Handle missing values.  
   - Encode categorical variables (`Sex`, `Embarked`).  
   - Feature scaling if necessary.  

3. **Model Training - Logistic Regression:**  
   - Train/test split.  
   - Fit Logistic Regression model.  
   - Make survival predictions.  

4. **Model Evaluation:**  
   - Accuracy score.  
   - Confusion matrix.  
   - Precision, Recall, and F1-score.  

---

## 📊 Results  

- Logistic Regression model gives a baseline accuracy of around **~77–80%** (varies by preprocessing).  
- Gender and Passenger Class are strong indicators of survival probability.  

---

## 🚀 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/EDA-ON-TITANIC-DATASET.git
   cd EDA-ON-TITANIC-DATASET


   
