# 🛳️ Titanic Survival Prediction – Machine Learning Project

## 📌 Overview
This project predicts passenger survival during the **Titanic disaster** using **machine learning techniques**.  
It demonstrates a complete **end-to-end ML pipeline**, including data preprocessing, feature engineering, model comparison, and evaluation.

The final model achieves **~84% accuracy**, making it reliable and interview-ready.

---

## 🎯 Problem Statement
Build a **binary classification model** to predict whether a passenger survived the Titanic disaster.

- **Target Variable:** `Survived`
  - `1` → Survived
  - `0` → Did Not Survive

---

## 📊 Dataset Information
- **Source:** Kaggle – *Titanic: Machine Learning from Disaster*
- **Total Records:** 891
- **Type:** Structured tabular dataset

### Key Features
- Pclass – Passenger class  
- Sex – Gender  
- Age – Age of passenger  
- SibSp – Siblings/Spouses aboard  
- Parch – Parents/Children aboard  
- Fare – Ticket fare  
- Embarked – Port of embarkation  

---

## 🛠️ Data Preprocessing
- Removed low-importance columns (`Cabin`, `Ticket`, `PassengerId`)
- Handled missing values using **group-based median imputation**
- Filled categorical missing values using **mode**
- Applied **One-Hot Encoding** for categorical features

---

## ⚙️ Feature Engineering
- **Title extraction** from passenger names (Mr, Mrs, Miss, Rare)
- **FamilySize** feature
- **IsAlone** indicator
- Age imputation based on **Sex & Passenger Class**

These steps significantly improved model performance.

---

## 🤖 Models Implemented
| Model | Accuracy |
|------|---------|
| Logistic Regression | ~78% |
| Random Forest (Tuned) | ~82–83% |
| Gradient Boosting | **~83–84%** |

---

## 🏆 Best Model
- **Gradient Boosting Classifier**
- **Final Accuracy:** ~84%
- Robust and effective for non-linear relationships

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🧠 Key Learnings
- Feature engineering greatly improves accuracy
- Ensemble models outperform baseline models
- Clean preprocessing is crucial for ML success

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run
Install dependencies:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:
```
Titanic.ipynb
```

---

## 📎 Dataset Reference
- Kaggle Titanic Dataset

---

⭐ *This project is ideal for ML portfolios, GitHub, Kaggle, and interviews.*
