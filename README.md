# 🚢 Titanic Survival Prediction — Machine Learning Project

## 📂 Overview

Predicting passenger survival from the Titanic disaster using machine learning methods and data science best practices.
This project covers **data cleaning**, **feature engineering**, **model training**, and **evaluation** using the iconic Titanic dataset.

---

## 🚀 Project Structure

```
text
├── README.md             <- You are here!
├── data/                 <- Data files (train, test, external sources)
├── notebooks/            <- Jupyter notebooks for EDA, modeling, visualization
├── outputs/              <- Model predictions and submission CSVs
```

---

## 💡 Problem Statement

Can we predict which passengers survived the sinking of the Titanic using demographic and ticketing data?
The goal is **binary classification**:

* **1** → Survived
* **0** → Did Not Survive

---

## 🔑 Key Topics Covered

| Topic                      | Note                                                                |
| -------------------------- | ------------------------------------------------------------------- |
| **Data Loading**           | Reading data into pandas, inspecting with `.info()` / `.describe()` |
| **EDA & Visualization**    | Survival rates, distributions using seaborn/matplotlib              |
| **Missing Value Analysis** | Detecting and imputing missing data                                 |
| **Data Cleaning**          | Dropping irrelevant columns, filling missing values (mean/mode)     |
| **Feature Engineering**    | `FamilySize`, `Title` extraction, removing noise features           |
| **Categorical Encoding**   | One-hot encoding, binary mapping (`Sex` → 0/1)                      |
| **Feature Scaling**        | Standardizing `Age`, `Fare`, `FamilySize`                           |
| **Train/Test Split**       | `train_test_split` for generalization                               |
| **Model Training**         | Logistic Regression, Random Forest                                  |
| **Model Evaluation**       | Accuracy, precision, recall, F1, confusion matrix                   |
| **Hyperparameter Tuning**  | `GridSearchCV` for best model search                                |
| **Prediction Export**      | Creating submission-ready CSVs                                      |
| **Pipeline Consistency**   | Ensuring uniform preprocessing for train/test sets                  |

---

## 📊 Results

* **Best accuracy:** ~80% using **Logistic Regression** after feature engineering + tuning
* Models generally predicted **non-survivors** more accurately (class imbalance effect)

---

## 📚 Data Source

* **Kaggle Titanic Competition**
