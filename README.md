# 📊 Telco Customer CLTV Prediction (WIP)

## 🚧 Project Status: Work In Progress

This project aims to **predict Customer Lifetime Value (CLTV)** using linear regression based on a fictional Telco Customer Churn dataset. It is designed as an end-to-end data science project that invole :

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Building (Linear Regression)  
- Model Evaluation and Interpretation

The dataset contains detailed customer information including demographics, service subscriptions, billing details, and churn-related scores. By focusing on CLTV prediction, the goal is to help the business identify high-value customers and make data-driven decisions to improve retention strategies.

---

## 🎯 Objective (as for now)

Use linear regression to **predict Customer Lifetime Value (CLTV)** based on various customer features such as service usage, demographics, and billing behavior.

---

## ✅ Skills Demonstrated

- 🧹 Data preprocessing (handling nulls, encoding, feature selection)
- 📊 EDA using Pandas, Matplotlib, and Seaborn
- ⚙️ Feature engineering from categorical and numerical data
- 📈 Linear regression modeling with scikit-learn
- 📉 Model evaluation using RMSE and R² Score
- 🧠 Business interpretation of regression coefficients

---

## 🔍 Next Steps

---

## 📁 Dataset

The dataset used is the **Telco Customer Churn Dataset**, which includes:
- Demographic info
- Service usage patterns
- Subscription types
- Customer behavior and churn risk
- Customer Lifetime Value (CLTV)

---

## 📌 Tools Used

---

## 🤝 Contributions & Feedback

---
<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         telco_customer_analysis and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── telco_customer_analysis   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes telco_customer_analysis a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

