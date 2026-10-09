<div align="center">

# 🏦 Loan Approval Prediction

**Predict whether a loan application will be approved by comparing several classifiers and combining them in an ensemble.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`app.ipynb` reads the applicant data from `data.xlsx`, then:

- 🔎 Explores and visualises the data (pandas, Seaborn).
- 🏷️ Encodes categorical features with a `ColumnTransformer`.
- 🤖 Trains and compares **Logistic Regression, KNN, Gaussian Naive Bayes, Gradient Boosting and Bagging** classifiers.
- 🗳️ Combines them with a **`VotingClassifier`** - the final ensemble reaches about **83 % accuracy**.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/loan-approval.git
cd loan-approval
pip install pandas numpy scikit-learn seaborn matplotlib openpyxl jupyter
jupyter notebook app.ipynb
```

## 📁 Project Structure

```
.
├── app.ipynb     # EDA, preprocessing, models, voting ensemble
└── data.xlsx     # Loan applicant data
```

## 🛠️ Tech Stack

`scikit-learn` · `pandas` · `Seaborn` · `Matplotlib`
