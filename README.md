
# 🚢 Titanic Survival Prediction

## 📌 Overview

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster using structured data such as age, gender, class, and fare.

---

## 🎯 Objective

* Perform data preprocessing and feature engineering
* Train a classification model
* Evaluate model performance using multiple metrics

---

## 🧠 Model

* Logistic Regression

---

## 🛠️ Tools & Libraries

* Python
* pandas
* scikit-learn
* matplotlib
* seaborn

---

## 📊 Dataset

* Titanic dataset (train.csv)
* Target variable: `Survived`

### Features used:

* Pclass
* Age
* SibSp
* Parch
* Fare
* Sex
* Embarked

---

## ⚙️ Data Preprocessing

* Filled missing values:

  * Age → mean
  * Fare → mean
  * Embarked → mode
* Dropped unnecessary columns:

  * Name, Ticket, Cabin
* Converted categorical variables using one-hot encoding:

  * Sex
  * Embarked

---

## 🤖 Model Training

* Split data into training and testing sets (80/20)
* Trained Logistic Regression model on training data

---

## 📈 Model Performance

| Metric               | Score |
| -------------------- | ----- |
| Accuracy             | 0.81  |
| Precision (Survived) | 0.76  |
| Recall (Survived)    | 0.74  |
| F1-score (Survived)  | 0.75  |

---

## 🔍 Confusion Matrix

* Model predicts non-survivors more accurately than survivors
* Some survivors are misclassified as non-survivors

---

## 💡 Key Insights

* Female passengers had a higher survival rate
* Higher fare is associated with higher survival probability
* Passenger class plays an important role in survival

---

## 🚀 Future Improvements

* Try other models (Decision Tree, KNN)
* Add new features (e.g., Family Size)
* Perform hyperparameter tuning
* Use cross-validation

---
