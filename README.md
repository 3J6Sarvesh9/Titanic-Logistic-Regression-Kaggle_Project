# 🚢 Titanic Survival Prediction (Machine Learning Project)

This project is a beginner-friendly Machine Learning model built using the famous Titanic dataset from Kaggle.  
The goal is to predict whether a passenger survived or not based on features like age, gender, class, etc.

---

## 📊 Problem Statement
Predict survival of passengers on the Titanic using classification algorithms.

---

## 📁 Dataset
Source: Kaggle Titanic Dataset  
Features include:
- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

---

## ⚙️ Steps Performed

### 1. Data Preprocessing
- Handled missing values (Age, Embarked)
- Dropped unnecessary columns (Cabin, Name, Ticket)
- Converted categorical data into numerical format

### 2. Feature Engineering
- Encoded `Sex` (male/female → 0/1)
- One-hot encoded `Embarked`

### 3. Model Building
- Algorithm used: Logistic Regression
- Library: Scikit-learn

### 4. Training
- Split data into training and testing sets
- Trained Logistic Regression model

### 5. Prediction
- Generated predictions on test dataset
- Created submission file for Kaggle

---

## 📦 Libraries Used
- pandas
- numpy
- scikit-learn

---

## 📈 Model Performance
- Evaluation metric: Accuracy (Kaggle leaderboard score depends on submission)
- Focus: Basic classification model

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
