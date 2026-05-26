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
