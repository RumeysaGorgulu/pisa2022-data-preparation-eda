# PISA 2022 — Data Preparation & EDA

Data preprocessing and exploratory analysis of the PISA 2022 Student Questionnaire dataset using R.

## What this covers
- Loading and converting the PISA 2022 SPSS file to RDS
- Missing data analysis and threshold-based filtering
- Country-level ESCS imputation
- Summary statistics and correlation analysis across 79 countries

## Data
Download the PISA 2022 Student Questionnaire (SPSS format) from:
https://www.oecd.org/pisa/data/

Place `CY08MSP_STU_QQQ.SAV` in the project root before running.

## Requirements
```r
install.packages(c("haven", "tidyverse", "stringr"))
```

## Author
Rumeysa Gorgulu
