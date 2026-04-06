# COMPAS Assignment 3 – Disparate Impact Audit

## Purpose of the Analysis
Hi professor, this assignment conducts a full disparate impact audit on the COMPAS recidivism risk scoring model. The goal is to measure bias across racial and gender groups using standardized fairness metrics and assess whether the model produces discriminatory outcomes.

## What this project does
This project audits the COMPAS model for disparate impact using multiple bias metrics. It computes AIR, ME, and SMD by race and sex, performs an intersectional analysis across race × sex subgroups, tests error-rate disparities (FPR and FNR) for statistical significance, and produces publication-quality visualizations of the findings.

## Python Libraries Used
* pandas
* numpy
* matplotlib
* statsmodels
* solas-ai (solas_disparity)

## Key Tasks Completed
* Computed AIR, ME, and SMD by race and sex using solas-ai and confirmed results manually
* Built an intersectional (race × sex) analysis and identified the worst-group AIR
* Computed FPR and FNR disparities by race with two-proportion z-tests
* Produced a grouped bar chart of FPR and FNR with Caucasian as the reference group
* Wrote a 300-word compliance memo addressed to a hypothetical regulator

## Key Insights
* African-American defendants have significantly higher FPR than Caucasian defendants (p < 0.001)
* Hispanic/Female subgroup shows the lowest intersectional AIR, well below the 0.80 threshold
* FPR and FNR disparities reflect a fairness trade-off that cannot be resolved simultaneously
* SMD confirms large distributional separation in risk scores between racial groups

## Instructions to Reproduce the Results
1. Open the Jupyter Notebook file (COMPAS_RML_HW3_Final.ipynb)
2. Run all cells from top to bottom
3. Results and figures will be generated automatically

Thanks professor .. Hassan Alshamrani
