# Customer Churn Prediction

This project demonstrates a complete machine learning workflow for predicting customer churn using Python. It includes data generation, preprocessing, model training, evaluation, and interpretation. The goal is to build a simple, clean, and easy-to-understand baseline model suitable for business decision-making.

---

## 📌 Project Overview

Customer churn prediction helps companies identify which customers are likely to leave.  
In this project, we:

- Created a synthetic telecom-style churn dataset  
- Explored data using pandas  
- Trained a Logistic Regression model  
- Evaluated model performance using standard classification metrics  
- Generated actionable insights for understanding churn behavior  

---

## 🧠 Machine Learning Steps

### **1. Data Generation**
A 2000-row dataset was generated using `make_classification` with realistic customer behavior features such as:

- Monthly charges  
- Tenure  
- Number of products  
- Support calls  
- Contract length  
- Usage and satisfaction scores  

Target variable:  
`churn` (1 = customer will leave, 0 = stay)

---

### **2. Preprocessing**
- Organized features into a DataFrame  
- Created feature matrix `X` and target vector `y`  
- Split into train and test sets  

---

### **3. Model Training**
Algorithm used:

- ✔ Logistic Regression (`sklearn.linear_model.LogisticRegression`)

Model achieved:

- **84.5% accuracy** on the test set  
- Balanced precision/recall for both classes  

---

### **4. Evaluation Metrics**
We used:

- Confusion Matrix  
- Accuracy Score  
- Classification Report  
  - Precision  
  - Recall  
  - F1-score  

These help assess real-world performance and potential model improvements.

---

## 📊 Results

- The model performs well as a **baseline churn classifier**  
- Shows balanced performance between positive/negative classes  
- Can be extended with:
  - Feature scaling  
  - Additional models (Random Forest, XGBoost)  
  - Hyperparameter tuning  
  - Real telecom datasets  

---

## 🛠 Tools & Technologies

- Python  
- NumPy  
- pandas  
- scikit-learn  
- Google Colab / Jupyter Notebook  
- GitHub  

---

## 📂 Repository Contents

