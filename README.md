# BiciMAD Hypothesis Testing with R

Statistical analysis and hypothesis testing on BiciMAD trip data using R. This project includes data cleaning, exploratory analysis, and t-tests to study trip duration patterns.

## Overview

The notebook performs:

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Outlier and invalid value removal
- One-sample and two-sample hypothesis testing
- Visualization of t-distributions and test statistics

The analysis is implemented in `main.ipynb`.

---

## Research Questions

### 1. Single Population Analysis
Tests whether the average duration of BiciMAD trips in March 2022 exceeds 12 minutes.

- **Test:** One-sample t-test  
- **H₀:** μ ≤ 12 minutes  
- **H₁:** μ > 12 minutes  

---

### 2. Two Population Analysis
Compares trip duration between weekend and weekday trips.

- **Test:** Two-sample t-test (independent samples)  
- **H₀:** μ_weekend ≤ μ_weekday  
- **H₁:** μ_weekend > μ_weekday  

---

## Data Preprocessing

The dataset is cleaned before analysis:

- Removal of duplicated records
- Removal of missing values
- Filtering negative and invalid trip durations
- Outlier detection and removal
- Weekday vs weekend classification

---

## Methods

- Exploratory Data Analysis
- One-sample t-test
- Two-sample t-test
- Statistical visualization of t-distributions
- Confidence intervals and hypothesis testing (α = 0.05)

---

## Technologies

- R
- tidyverse / dplyr
- lubridate
- Statistical inference methods

---

## Repository Structure

- main.ipynb # Main analysis notebook
- trips_22_03_March.csv # Dataset
