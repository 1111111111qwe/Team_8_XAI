#  Heart Disease Prediction with Explainable AI (XAI)

> A machine learning project that predicts heart disease risk using multiple classification algorithms, paired with explainability techniques to make model decisions transparent and interpretable.

---

##  Overview

Cardiovascular disease remains one of the leading causes of death worldwide. Early and accurate prediction can save lives — but in healthcare, **why** a model makes a decision is just as important as the decision itself.

This project builds a complete end-to-end ML pipeline for heart disease prediction, then applies **Explainable AI (XAI)** techniques (SHAP, LIME, and others) to interpret and justify the models' predictions. The work was done collaboratively by **Team 8** as part of an applied ML/XAI course.

---

##  Repository Structure

```
Team_8_XAI/
│
├── Team-8-preprocessing-EDA.ipynb              # Data ingestion, EDA, and preprocessing
├── Team8_Mohamed_ashraf_M1.ipynb               # Milestone 1: Initial modeling
├── Team8_Mohamed_Ashraf_M2_(1)_(1).ipynb       # Milestone 2: Model improvement
├── Team8_Mohamed_ashraf_M3.ipynb               # Milestone 3: Advanced experiments
├── Team_8_Mohamed_Bekheit_RF_LR_CARTipynb.ipynb # Random Forest, Logistic Regression, CART
├── Team_8_Tasneem_Ashraf_Final_Project.ipynb   # Final integrated project notebook
├── Team_8_mid_progress_Mahmoud_Tarek.ipynb     # Mid-project progress checkpoint
├── heart_mlp_explainability (1).ipynb          # XAI on MLP (Multi-Layer Perceptron)
└── heart_naive_bayes_explainability (1).ipynb  # XAI on Naive Bayes
```

---

## Pipeline Stages

The project follows a structured ML pipeline:

1. **Data Ingestion** — Loading and inspecting the heart disease dataset
2. **Exploratory Data Analysis (EDA)** — Distributions, correlations, class balance
3. **Preprocessing** — Handling missing values, encoding, scaling
4. **Outlier Detection** — Identifying and treating anomalies
5. **Feature Engineering & Selection** — Creating and selecting the most predictive features
6. **Model Training & Evaluation** — Training multiple classifiers and comparing performance
7. **Explainability (XAI)** — Interpreting model decisions using SHAP, LIME, and feature importance

---

##  Models Used

| Model | Notebook |
|---|---|
| Random Forest Classifier | `Team_8_Mohamed_Bekheit_RF_LR_CARTipynb.ipynb` |
| Logistic Regression | `Team_8_Mohamed_Bekheit_RF_LR_CARTipynb.ipynb` |
| CART (Decision Tree) | `Team_8_Mohamed_Bekheit_RF_LR_CARTipynb.ipynb` |
| CatBoost | Various milestone notebooks |
| LightGBM | Various milestone notebooks |
| XGBoost | Various milestone notebooks |
| Multi-Layer Perceptron (MLP) | `heart_mlp_explainability (1).ipynb` |
| Naive Bayes | `heart_naive_bayes_explainability (1).ipynb` |

---

##  Explainability (XAI) Techniques

A core goal of this project is not just prediction accuracy but **model transparency**. The following XAI methods are applied:

- **SHAP (SHapley Additive exPlanations)** — Global and local feature importance, summary plots, force plots
- **LIME (Local Interpretable Model-agnostic Explanations)** — Per-sample explanation of predictions
- **Feature Importance Plots** — Tree-based and permutation importance
- **Decision boundary visualization** — For simpler models like CART and Logistic Regression
- **pdp**
- **LOFO**

---

##  Dataset

The project uses a **heart disease dataset** (likely the UCI Heart Disease / Cleveland dataset or a similar clinical dataset), which includes features such as:

- Age, Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression (Oldpeak)
- Target: Presence or absence of heart disease

---

##  Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm catboost shap lime jupyter
```

### Running the Notebooks

Clone the repo and open the notebooks in order:

```bash
git clone https://github.com/1111111111qwe/Team_8_XAI.git
cd Team_8_XAI
jupyter notebook
```



---

##  Key Outcomes

- Comprehensive comparison of **12 classification models** on heart disease data
- Identification of the **most important clinical features** driving predictions
- Transparent, interpretable predictions using SHAP and LIME suitable for a **clinical context**
- Demonstrated that ensemble methods (Random Forest, XGBoost, LightGBM, CatBoost) consistently outperform simpler baselines while remaining interpretable

---

##License

This project was developed for academic purposes. Please contact the contributors before reusing any part of the work.

---

*
