# 🛍️ Shopping Intent Prediction

Predict whether a website visitor will make a purchase based on their
browsing behavior.\
This project walks through a full machine-learning pipeline inside the
notebook:

> **shopping_intent.ipynb**

It includes data cleaning, feature engineering, class-imbalance
handling, model building, tuning, and evaluation.

## 🎯 Objectives

-   Analyze user behavior patterns\
-   Predict the target variable **MadePurchase** (Yes/No)\
-   Resolve missing values and outliers\
-   Handle class imbalance using **SMOTE**\
-   Compare multiple ML models\
-   Choose and tune the best performer

## 🧰 Tech Stack

-   Python
-   Pandas, NumPy
-   Matplotlib / Seaborn
-   Scikit‑learn
-   Imbalanced‑learn (SMOTE)

## 📂 Project Structure

    shopping_intent.ipynb   # Main notebook
    README.md               # Project documentation

## 🔎 Workflow

1.  Data Understanding & EDA\
2.  Data Cleaning\
3.  Feature Engineering\
4.  Encoding & Scaling\
5.  Class Balancing (SMOTE)\
6.  Modeling\
7.  Hyperparameter Tuning\
8.  Final Model Selection

## ▶️ How to Run

Install dependencies:

    pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn

Open the notebook:

    jupyter notebook shopping_intent.ipynb

## 📈 Results (Overview)

Gradient Boosting showed the strongest performance after handling
imbalance and tuning.

## 🚧 Future Improvements

-   Add explainability tools (SHAP)
-   Deploy as API / dashboard
-   Try more advanced ensemble models

Feel free to modify or extend!
