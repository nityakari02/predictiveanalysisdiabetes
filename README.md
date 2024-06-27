# Predictive Analysis of Diabetes in Pima Indian Females Using Diagnostic Measurements

## Project Description

This project focuses on performing a predictive analysis of diabetes using diagnostic measurements from a dataset of Pima Indian females. The primary goal is to identify whether diagnostic measurements can accurately predict the presence of diabetes. By exploring these predictions, we aim to gain insights into the relationship between various health metrics and diabetes status.

## Project Components

1. **R Markdown File (PredictiveAnalysisDiabetes.Rmd):** 
   This file contains the complete R code used for the predictive analysis. It includes sections for loading and preparing the dataset, performing the analysis using logistic regression, and visualizing the results.

2. **CSV Data File (diabetes.csv):**
   The dataset consists of health measurements from Pima Indian females. It includes variables such as the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and diabetes status.

3. **PDF Report (PredictiveAnalysisDiabetes.pdf):**
   A comprehensive report that summarizes the findings of the predictive analysis. It includes visualizations and discussions on the results.

## Research Question

The core research question driving this analysis is: *"Can diagnostic measurements accurately predict whether a Pima Indian female has diabetes?"* The investigation aims to explore the relationship between health metrics and diabetes status.

## Analysis Steps

- **Data Loading:** The dataset is loaded into R and essential packages for data analysis and visualization are imported.
- **Data Wrangling:** Relevant variables are selected, renamed, and cleaned to prepare for analysis.
- **Predictive Analysis:** Logistic regression is performed to predict diabetes status based on diagnostic measurements. The model's accuracy and performance metrics are evaluated.
- **Visualization:** The results of the analysis are visualized to interpret and understand the patterns and relationships within the data.
- **Discussion:** The findings are discussed, highlighting the significance of the predictive model and the implications for diabetes diagnosis.

## Technologies and Skills Used

- **Programming Languages:** R
- **Libraries and Packages:**
  - **Data Manipulation and Wrangling:**
    - `tidyverse`: Comprehensive collection of packages for data manipulation and wrangling.
  - **Predictive Analysis:**
    - `caret`: For performing logistic regression and evaluating model performance.
    - `rms`: For additional regression modeling and diagnostics.
  - **Visualization:**
    - `factoextra`: For visualizing PCA results.
    - `ggplot2`: For creating detailed and customized data visualizations.
- **Data Analysis Skills:** 
  - Data wrangling and preprocessing.
  - Logistic regression modeling.
  - Evaluating model performance.
  - Data visualization and interpretation.
- **Tools:** RStudio for coding and analysis, GitHub for version control and project sharing.

## Requirements

- R
- R libraries: factoextra, caret, rms, tidyverse, ggplot2

## How to Run

To replicate the analysis, open the `PredictiveAnalysisDiabetes.Rmd` file in RStudio and knit the document. Ensure that the necessary R libraries are installed.

## Results

The analysis demonstrates that diagnostic measurements can effectively predict the diabetes status of Pima Indian females, with significant implications for early diagnosis and intervention. This project highlights the importance of machine learning and statistical analysis in public health research.
