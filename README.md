# 🚢 Titanic Survival Prediction

A beginner-friendly machine learning project based on the famous Titanic dataset from Kaggle.

The goal is to predict whether a passenger survived the Titanic disaster using passenger information such as age, gender, passenger class, fare, and family details.

## 📌 Project Overview

This project covers the complete basic machine learning workflow:

- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Missing value handling
- Feature engineering
- Categorical encoding
- Train-validation split
- Logistic Regression
- Random Forest
- Cross-validation
- Hyperparameter tuning
- Kaggle submission

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Features Used

Some of the features used in the model:

- Passenger Class (`Pclass`)
- Sex
- Age
- Fare
- Siblings/Spouses (`SibSp`)
- Parents/Children (`Parch`)
- Family Size
- Is Alone
- Embarked Port
- Deck
- Passenger Title

## 🤖 Models

### Logistic Regression
Used as the primary baseline classification model.

### Random Forest
Tested as an alternative model.

Logistic Regression performed better on the validation data for this version of the project.

## 📊 Results

| Model | Validation / CV Score |
|---|---:|
| Logistic Regression | ~82.49% |
| Random Forest | ~80.70% |

### Kaggle Score

**77.27%**

This was my first version of the Titanic ML project and serves as a baseline for future improvements.

## 📁 Project Structure

```text
Titanic-ML/
│
├── main.ipynb
├── train.csv
├── test.csv
├── submission.csv
└── README.md
