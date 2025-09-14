# Data Science Assignment – Extensions of the Linear Model

This folder contains my solutions for the **Introduction to Data Science** assignment, which consisted of two analyses written as research-style reports. The work was implemented in R using Jupyter notebooks and summarized in the accompanying PDF report.

## Contents
- `assign_1_ANOVA_students_and_teaching_methods_R.ipynb`  
- `assign2_adult_pima_indians_diabetis_predictors_gam_R.ipynb`  
- `Assignment_DS.pdf` – official assignment requirements  
- `report_Ivan_Al_Khayat_Assignment.pdf` – written report of my results  

## Exercise 1: Mixed-Effects ANOVA
- **Goal:** Investigate whether teaching method (fixed effect) influences student performance while accounting for school-level differences (random effect).  
- **Approach:**  
  - Performed exploratory data analysis (histograms, boxplots).  
  - Fitted a two-factor mixed-effects ANOVA model with teaching method as fixed and school as random.  
  - Evaluated the significance of teaching methods and variance attributable to schools.  
- **Findings:** Teaching methods showed a measurable impact on performance, with schools also contributing variance.

## Exercise 2: Generalized Additive Models (GAM)
- **Goal:** Analyze predictors of diabetes using the *Pima Indians Diabetes* dataset (and Adult dataset extensions).  
- **Approach:**  
  - Preprocessed and explored predictor distributions.  
  - Fitted GAMs to model nonlinear effects of predictors on diabetes outcome.  
  - Visualized smooth functions for interpretability.  
  - Assessed predictor significance and model fit.  
- **Findings:** Several predictors (e.g., glucose, BMI, age) were highly significant, with GAMs capturing nonlinear trends that standard linear models might miss.

## How to Use
Open the notebooks in Jupyter and run the R code cells sequentially. All required datasets are assumed to be available as in the original assignment instructions.

---
*Author: Ivan Al Khayat*