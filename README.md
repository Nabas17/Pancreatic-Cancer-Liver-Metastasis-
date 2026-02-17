# Pancreatic Cancer Liver Metastasis Risk Study

This repository contains the analysis code and notebooks for our study:  
**“Characterization of Liver Metastasis Risk and Timing in Pancreatic Cancer Using Electronic Health Records”**  
[medRxiv preprint](https://www.medrxiv.org/content/10.1101/2025.10.31.25339268v2.full-text)

## Overview

A cohort of 12,955 incident pancreatic cancer patients was assembled from the Truveta electronic health record (EHR) platform. This study aimed to identify clinical and demographic risk factors associated with the development of liver metastasis (LM), stratified by timing of occurrence. Logistic regression and Cox proportional hazards models were used to analyze LM risk and timing, including a composite endpoint of LM or death to account for under-documentation.

## Primary Analyses

- **Logistic Regression**: Assessed risk factors for liver metastasis occurring within one year of pancreatic cancer diagnosis.
- **Cox Regression**: Evaluated time to metastasis, distinguishing between baseline (≤30 days from diagnosis) and post-baseline (>30 days) liver metastasis.

## Repository Contents

| File | Description |
|------|-------------|
| `BMI_Derivation.ipynb` | Derives body mass index (BMI) values from height and weight records using EHR data. |
| `CohortCreation.ipynb` | Defines inclusion/exclusion criteria and assembles the final pancreatic cancer cohort. |
| `Covariates.ipynb` | Generates demographic and clinical covariates, including comorbidities (e.g., diabetes, obesity, anemia). |
| `Lab_test.ipynb` | Extracts and cleans laboratory test values relevant to the study. |
| `Regression&Tables.ipynb` | Performs logistic and Cox regression analyses; generates result tables for the manuscript. |
| `README.md` | This file, summarizing the repository structure and study. |

## Key Features

- Real-world data analysis using EHR from the Truveta platform
- Rigorous cohort construction and covariate derivation
- Timing-stratified analysis of liver metastasis
- Reproducible code organized by task

## Citation

Talukdar N, Yu Z, Zeng Z, Zhang X, Lu Y, Joseph D, Leshchiner D, Wang H, Chen B.  
**Characterization of Liver Metastasis Risk and Timing in Pancreatic Cancer Using Electronic Health Records.**  
*medRxiv*. 2025. [https://doi.org/10.1101/2025.10.31.25339268](https://doi.org/10.1101/2025.10.31.25339268)

---
