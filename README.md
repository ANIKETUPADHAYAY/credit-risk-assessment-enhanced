# 💳 Credit Risk Assessment using Probability, Statistics & Machine Learning Enhanced

![Python](https://img.shields.io/badge/Python-3.10-yellow.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

This project analyzes credit risk using the **LendingClub dataset**. It combines **Probability & Statistics** with **Machine Learning** to predict the likelihood of loan defaults, aiming to empower better financial decisions and risk management.

*Note: This repository is an enhanced study based on existing open-source work, focused on exploring additional statistical models and feature engineering techniques.*

---

## 🎯 Project Overview

In the digital financial landscape, lending institutions rely on **data-driven strategies** to evaluate creditworthiness. This project leverages **probability**, **statistics**, and **machine learning** to build a robust system for **Credit Risk Assessment**.

### Key Objectives

- **Real-World Application**: Analyzing structured loan data to understand risk factors in peer-to-peer lending.
- **Statistical Analysis**: Applying feature engineering and statistical modeling to financial data.
- **Interpretability**: Focusing on explainable patterns using probability distributions and visualizations to understand *why* loans default.

---

## 📊 Exploratory Data Analysis (EDA)

The analysis includes:
- **Distributions**: Histograms and Box Plots to understand data spread and outliers.
- **Relationships**: Violin & Scatter Plots analyzing `interest rate`, `FICO scores`, and `loan status`.
- **Feature Importance**: Using Mutual Information and Random Forest importance to identify key predictors.

---

## 🧠 Modeling Approach

The project evaluates classifier performance using metrics like AUC Score and ROC Curves.

**Models Analyzed:**
- Logistic Regression
- Random Forest Classifier
- *Future/Ongoing Work:* Implementation of Gradient Boosting (XGBoost) for comparative analysis.

### ✅ Techniques

- **Feature Selection**: Recursive Feature Elimination and Mutual Information.
- **Evaluation**: Confusion Matrix, Cross-validation, and AUC Scores.

---

## 📌 Key Findings

- **Interest Rates**: Higher rates are strongly correlated with default risk.
- **FICO Scores**: Lower scores are a primary indicator of default likelihood.
- **Recoveries**: Features like `collection_recovery_fee` are strongly associated with defaulted loans.
- **Predictive Power**: `int_rate` and `fico_range_low` consistently rank as top predictive features.

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| `CreditRiskUsingProbability&Statistics.ipynb` | Main notebook containing EDA, modeling, and evaluation |
| `README.md` | Project documentation |
| `LICENSE` | MIT License |
| `requirements.txt` | Python dependencies |
| `dataset/` | Data files |

---

## 📚 Dataset

The dataset is sourced from the [Give Me Some Credit – Kaggle Competition](https://www.kaggle.com/competitions/GiveMeSomeCredit/data).

---

## ⚙️ Tech Stack

- **Language**: Python 3.10
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment**: Jupyter Notebook / Google Colab

---

## 🚀 Future Scope & Modifications

To further differentiate this analysis, the following improvements are planned:
- **Advanced Modeling**: Integration of Ensemble techniques like XGBoost and LightGBM.
- **Hyperparameter Tuning**: Using GridSearchCV for optimal model performance.
- **Imbalance Handling**: Applying SMOTE to handle class imbalance in default data.

---

## 👤 Author

**Aniket Kumar Upadhayay**
- 📧 [aniketkumar00108@gmail.com](mailto:aniketkumar00108@gmail.com)

---

## 🤝 Acknowledgements & License

This project is open-source and licensed under the [MIT License](LICENSE).
