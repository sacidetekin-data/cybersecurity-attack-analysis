![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=flat&logo=python&logoColor=white)

# Cybersecurity Attack Analysis using Machine Learning

## 📌 Project Overview

This project analyzes cybersecurity network traffic data to classify cyber attacks using machine learning techniques.  

The initial goal was multi-class classification of different attack types. However, baseline models showed low performance (~33% accuracy), indicating limited feature separability.

The problem was then reframed as a binary classification task (Normal vs Attack), improving performance significantly.

---

## 📊 Dataset

- 40,000 network traffic records  
- 29 features  
- Includes protocol, port information, anomaly scores, traffic type and system logs  

Target variable: **Attack Type**

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Removed irrelevant text-heavy features
- Handled missing values
- Encoded categorical variables
- Dropped IP-based identifiers to prevent noise

### 2️⃣ Modeling Approaches

Models tested:

- Decision Tree
- Random Forest
- Logistic Regression

### 3️⃣ Problem Reframing

Multi-class classification performance was low (~33%).  
The task was reframed into:

- 0 → Normal Traffic  
- 1 → Attack  

Random Forest model achieved:

> ✅ **66% Accuracy (Binary Classification)**

---

## 📈 Visualizations

- Confusion Matrix
- Binary Confusion Matrix
- Feature Importance (Random Forest)

---

## 💡 Key Insights

- Feature engineering and problem formulation significantly impact model performance.
- Binary classification improved detectability of attack behavior.
- Network-level attributes contribute differently to classification performance.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Advanced encoding techniques
- SMOTE for class balancing
- Deep learning approaches

---

## 👩‍💻 Author

Sacide Tekin  
Junior Data Analyst Candidate
