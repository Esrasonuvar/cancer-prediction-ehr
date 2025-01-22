# cancer-prediction-ehr
# Analysis of Cancer Risk Factors with Machine Learning on National Electronic Health Records

This repository contains the code, data, and documentation for the master's thesis titled **"Analysis of Cancer Risk Factors with Machine Learning on National Electronic Health Records"** by Esra Tokur Sonuvar. The research focuses on leveraging machine learning (ML) algorithms to predict cancer risk using Turkey’s national electronic health record system, e-Nabız.

## Overview

Cancer is a global health challenge, and early detection is critical for improving outcomes. This study utilizes machine learning techniques to analyze demographic, biochemical, and clinical data to identify cancer risk factors. By integrating large-scale health data with predictive models, the research highlights the transformative potential of ML in healthcare.

## Key Features

- **Data Preprocessing Pipeline**: Includes data cleaning, transformation, and feature selection steps, summarized in [Figure 1](./path_to_figure).
- **Machine Learning Algorithms**: Logistic Regression, Support Vector Machines (SVM), XGBoost, Random Forests, and Artificial Neural Networks (ANN).
- **Performance Metrics**: Evaluated using metrics such as accuracy, sensitivity, specificity, F1-score, and AUC-ROC.
- **Feature Importance Analysis**: Identifies critical predictors, including demographic features, lab test results, and ICD-10 codes.

## Data

The dataset was obtained from Turkey’s national EHR system, **e-Nabız**, covering records from 2018 to 2022. It includes:

- Demographic data: Age, gender, and region.
- Biochemical data: Blood test results (e.g., ALT, AST, HGB, PLT).
- Clinical data: ICD-10 codes and cancer diagnosis status.

Data preprocessing steps resulted in a structured dataset with 43 variables and 6,439,825 rows, reduced to 8 primary variables and 137 ICD-10 codes for model training.

## Results

- **Top-Performing Model**: XGBoost achieved the highest AUC-ROC of 0.846, demonstrating its efficacy in predicting cancer risk.
- **Feature Importance**: Key predictors include hemoglobin (HGB), alanine aminotransferase (ALT), and gender.

For more details, refer to the thesis documentation in the repository.

https://tez.yok.gov.tr/UlusalTezMerkezi/ title: "Analysis of cancer risk factors with machine learning on national electronic health records"

