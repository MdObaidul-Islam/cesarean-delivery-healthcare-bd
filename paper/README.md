# Conference Abstract & Presentation

This directory contains the conference abstract, presentation details, and citation information associated with this research project.

---

## Conference Details
* **Conference:** International Conference on Emerging Frontiers in Advanced Sciences and Technologies 2026 (**EFAST 2026**)
* **Conference Date:** 27–28 June 2026
* **Presentation Type:** Oral Presentation
* **Abstract:** Published in the official EFAST 2026 conference booklet

---

## Research Title
**Socioeconomic Determinants of Cesarean Section Delivery in Bangladesh: A Survey-Weighted Statistical and Explainable Machine Learning Analysis**

### Authors
**Md. Obaidul Islam**$^1$, **Md. Razu Ahmed**$^1$, and **Sabba Ruhi**$^{1,2,*}$

### Affiliations
1. Deep Statistical Learning and Research (DSLR) Lab, Department of Statistics, Pabna University of Science and Technology, Pabna-6600, Bangladesh
2. Department of Statistics, Pabna University of Science and Technology, Pabna-6600, Bangladesh

* **Presenting Author:** `obaidulislam0325@gmail.com`
* **Corresponding Author:** `sabba.ruhi@pust.ac.bd`

---

## Abstract Summary

### Study Design
This study investigates socioeconomic, maternal, and healthcare-system determinants of cesarean section delivery in Bangladesh using nationally representative **Bangladesh Demographic and Health Survey (BDHS) 2022** data.

The study applies a three-stage analytical framework combining:
1. **Survey-weighted Generalized Estimating Equations (GEE)** for population-representative statistical inference.
2. **Machine learning classification** using stratified cross-validation and Youden's J-based threshold optimization.
3. **SHapley Additive exPlanations (SHAP)** for global and individual-level model interpretability.

---

### Key Findings
* **Analytical Sample:** $N = 5,052$ women
* **National Cesarean Prevalence:** $44.65\%$
* **Private Facility Cesarean Prevalence:** $84.3\%$
* **Home Delivery:** Cesarean prevalence remained near zero
* **Strongest Bivariate Association:** Delivery facility type ($\text{Cramér's } V = 0.763$)

#### Adjusted Associations

| Predictor | Adjusted Odds Ratio (AOR) |
| :--- | :---: |
| Richest wealth quintile | **1.78** |
| $\ge 4$ antenatal care visits | **1.64** |
| Fourth-or-higher birth order | **0.48** |

*Regional variation in cesarean delivery also remained significant after adjustment.*

---

### Predictive Performance
The **Stacking Ensemble** achieved the best overall balance among the evaluated predictive models:
* **ROC-AUC:** $0.924$
* **F1-score:** $87.06\%$
* **Recall:** $91.22\%$

*SHAP analysis identified delivery facility type, wealth status, and birth order as the most influential predictors.*

---

## Conference Presentation
The study was presented as an **oral presentation** at **EFAST 2026**, and the abstract was included in the official conference booklet.

This repository contains the analytical workflow and supporting materials developed for the study.

---

## Citation
If you reference this conference abstract or the associated research, please cite:

```bibtex
@inproceedings{islam2026efast,
  author    = {Islam, Md. Obaidul and Ahmed, Md. Razu and Ruhi, Sabba},
  title     = {Socioeconomic Determinants of Cesarean Section Delivery in Bangladesh: A Survey-Weighted Statistical and Explainable Machine Learning Analysis},
  booktitle = {International Conference on Emerging Frontiers in Advanced Sciences and Technologies (EFAST 2026)},
  year      = {2026},
  address   = {Pabna, Bangladesh},
  note      = {Abstract published in the EFAST 2026 conference booklet}
}
89  }
90  ```
91  
92  ---
93  
94  ## Publication Status
95  * **Status:** Conference Abstract — Published in EFAST 2026 Conference Booklet
96  * **Note:** No full paper was prepared or submitted for this conference presentation.
