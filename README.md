# Female Genital Schistosomiasis (FGS) Knowledge, Attitudes, and Practices (KAP) Study

## Overview
This repository contains the R script used to analyse survey data from a 
Knowledge, Attitudes, and Practices (KAP) study on Female Genital 
Schistosomiasis (FGS) among healthcare workers in primary health care 
facilities (N = 60).

## Study Aim
To assess healthcare workers' awareness, knowledge, attitudes, practices, 
and perceived barriers regarding the diagnosis and management of FGS.

## Repository Contents
- `FGS_KAP_Analysis.R` — Main R script for data cleaning, descriptive 
  statistics, knowledge scoring, logistic regression, and figure generation.
- `README.md` — Project description and instructions.
- `LICENSE` — Licensing information.

## Data
The input dataset (`HW_FGS_KAP.xlsx`) is **not included** in this repository 
due to participant confidentiality. De-identified data may be made available 
from the corresponding author upon reasonable request.

## Requirements
- R version ≥ 4.2.0
- RStudio (recommended)

### Required R Packages
```r
install.packages(c(
  "tidyverse", "janitor", "gtsummary", "broom", "MASS", "ordinal",
  "skimr", "readxl", "dplyr", "tidyr", "stringr", "ggplot2", "gt",
  "EMT", "flextable", "officer", "forcats", "scales"
))


How to Run
Clone or download this repository.
Place the dataset HW_FGS_KAP.xlsx in your working directory.
Open FGS_KAP_Analysis.R in RStudio.
Update the setwd() path at the top of the script to match your folder.
Run the script section by section.

Outputs
The script generates:

Demographic and descriptive tables (Word format)
Knowledge, attitude, and practice summary tables
Logistic regression results (Odds Ratios with 95% CI)
Forest plots and bar charts (Word and PNG)

Author
Christianah Oki
Parasitology Research Unit, Department of Zoology, University of Ibadan, Nigeria 
christianaoki17@gmail.com

Citation
If you use this code, please cite:

Christianah Oki. (2026). Female Genital Schistosomiasis KAP Analysis
[R script]. GitHub. https://github.com/Christianah100/Female_Genital_Schistosomiasis_KAP

Christianah Oki. (2025). Female Genital Schistosomiasis KAP 
Analysis (Version v1.0.0) [R script]. Zenodo. 
https://doi.org/10.5281/zenodo.20396524
