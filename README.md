# Stroke-Data-Analysis

Introduction

This repository contains the code and analysis for predicting the likelihood of a patient experiencing a stroke based on various input parameters including gender, age, various diseases, and smoking status. Stroke is the second leading cause of death globally, responsible for approximately 11% of total deaths (according to the World Health Organization - WHO). This project aims to explore and analyze a dataset related to stroke and build a predictive model to identify potential risk factors.

Dataset

The dataset used for this analysis can be found in the data directory. It includes the following columns:

id: Unique identifier for each patient

gender: Gender of the patient (Male/Female/Other)

age: Age of the patient

hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension

heart_disease: 0 if the patient doesn't have any heart disease, 1 if the patient has heart disease

ever_married: Whether the patient has ever been married (Yes/No)

work_type: Type of work the patient is engaged in (Private, Self-employed, Govt_job, Children, Never_worked)

Residence_type: Type of residence of the patient (Urban/Rural)

avg_glucose_level: Average glucose level in the patient's blood

bmi: Body Mass Index of the patient

smoking_status: Patient's smoking status (formerly smoked, never smoked, smokes, Unknown)

stroke: 1 if the patient had a stroke, 0 if not (target variable)

Analysis

The key steps include:

Data Preprocessing: Cleaning and preparing the dataset for analysis.

Exploratory Data Analysis (EDA): Visualizing and understanding the distribution of variables, relationships, and potential insights.

Feature Engineering: Creating relevant features or transforming existing ones.

Model Building: Developing predictive models using machine learning algorithms.

Model Evaluation: Assessing the model's performance using appropriate metrics.

Conclusion: Summarizing the findings and drawing insights into the factors contributing to stroke risk.

Conclusion

This project provides a comprehensive analysis of stroke prediction based on patient characteristics. The predictive model developed in this project can be valuable for healthcare professionals in identifying individuals at risk of stroke, allowing for timely intervention and prevention.
