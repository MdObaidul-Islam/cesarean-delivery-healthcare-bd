# Cesarean Delivery Analysis in Bangladesh: Survey-Weighted Modeling, Machine Learning, Causal Inference & Explainable AI

[![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview
This repository contains the complete analytical workflow for studying socioeconomic, maternal, and health-system determinants of cesarean delivery in Bangladesh using nationally representative **Bangladesh Demographic and Health Survey (BDHS) 2022** data.

The study integrates survey-weighted statistical modeling, machine learning classification, causal inference frameworks, Explainable AI (SHAP), and rigorous **robustness & sensitivity testing** to identify key predictors of cesarean delivery, evaluate potential causal pathways, and ensure model stability for public health policy.

---

## Key Features

* **Survey-Weighted Statistical Analysis:** Accounts for complex survey sampling design, primary sampling units (PSUs), and sampling weights to obtain nationally representative estimates.
* **Statistical Modeling:** Examines associations between socioeconomic, maternal, and health-system factors and cesarean delivery using survey-weighted regression-based methods.
* **Causal Inference:** Incorporates propensity-score methods, doubly robust estimation, and causal forest analysis to investigate potential causal relationships.
* **Machine Learning:** Compares multiple classification algorithms, including Logistic Regression, SVM, Random Forest, XGBoost, AdaBoost, Extra Trees, and ensemble learning.
* **Explainable AI (XAI):** Uses SHAP (SHapley Additive exPlanations) to identify, visualize, and interpret the most influential predictors of cesarean delivery.
* **Robustness & Sensitivity Analysis:** Conducts extensive model stability checks, threshold optimization, weight perturbation, and subsample sensitivity analyses to evaluate predictive robustness and prevent overfitting.

---

## Repository Structure

```text
cesarean-delivery-healthcare-bd/
│
├── data/
│   └── README.md              # Instructions for obtaining BDHS 2022 data
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_statistical_modeling.ipynb
│   ├── 04_machine_learning.ipynb
│   ├── 05_shap_analysis.ipynb
│   └── 06_robustness_and_sensitivity_tests.ipynb
│
├── src/
│   ├── preprocessing.py       # Data cleaning & survey weight scaling
│   ├── statistical_models.py  # Weighted regression scripts
│   ├── ml_models.py           # Training & hyperparameter tuning
│   ├── explainability.py      # SHAP feature importance & visualization
│   └── robustness.py          # Model stability & sensitivity evaluation
│
├── results/
│   ├── figures/               # High-resolution ROC, SHAP, Causal & Robustness plots
│   └── tables/                # Summary tables & evaluation metrics (.csv/.tex)
│
├── paper/
│   └── README.md              # Publication details & citation guidelines
│
├── README.md                  # Main project documentation
├── requirements.txt           # Python dependencies
├── LICENSE                    # MIT License
└── .gitignore                 # Excluded files (data files, raw inputs)
[BDHS 2022 Data] ──► [Survey Weight Adjustment & Preprocessing]
                                   │
                                   ├──► [Survey-Weighted Statistical Modeling]
                                   ├──► [Causal Inference Framework]
                                   └──► [ML Benchmarking (XGBoost, RF, SVM)]
                                                   │
                                     [SHAP & Robustness Evaluation]
                                                   │
                                     [Policy & Public Health Insights]
---

## Data Availability
The primary raw dataset used in this study is sourced from the **Bangladesh Demographic and Health Survey (BDHS) 2022**. Due to data sharing policies and copyright restrictions of DHS Program, raw survey data files are not redistributed in this repository. 

Authorized researchers can request access directly from the [DHS Program Website](https://dhsprogram.com/). Instructions for setting up the raw data within the pipeline are provided in [`data/README.md`](data/README.md).

---

## Authors & Citation

**Md. Obaidul Islam**  
*Data Science & Machine Learning Researcher*  
Email: obaidulislam0325@gmail.com  

If you find this repository or methodology useful in your research, please cite as follows:

```bibtex
@misc{islam2026cesarean,
  author = {Islam, Md. Obaidul},
  title = {Cesarean Delivery Analysis in Bangladesh: Survey-Weighted Modeling, Machine Learning, Causal Inference, Explainable AI & Robustness Analysis},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{https://github.com/MdObaidul-Islam/cesarean-delivery-healthcare-bd}}
}
```

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
