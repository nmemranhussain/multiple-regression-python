Health Premium Prediction Model
Overview
This repository hosts a multiple regression model created as part of the DNSC 6303 course project at George Washington University. The goal of the model is to predict health insurance premiums based on various health-related independent variables.

Dataset
The dataset, sourced from Quiz 1 of DNSC 6303, includes health-related indicators:

Dependent Variable: Health premium received
Independent Variables:
Patient Age
Diabetes status
Blood pressure problem
Transplants
Chronic disease status
Patient's weight and height
Known allergies
Project Goals
The regression analysis focuses on:

Loading and exploring the dataset.
Splitting data into training and test sets (80:20 ratio).
Fitting the multiple regression model.
Performing residual analysis to validate model assumptions.
Generating insights into which variables significantly impact health premiums.
Key Findings
Significant Predictors: Age, transplants, chronic diseases, and weight were identified as key drivers affecting health premiums.
Insignificant Predictors: Blood pressure issues, patient height, and known allergies did not show a statistically significant effect.
Model Performance: The model's R-squared value of 0.694 suggests that approximately 69.4% of the variation in health premiums is explained by the independent variables.
Repository Structure
Data Files: Contains the main dataset payor.csv.
Notebooks: 6303_project.ipynb includes the data preprocessing, model training, and analysis.
Presentation: A project summary presentation in DNSC 6303 - Programming for Analytics I_presentation.pdf.
Future Work
Potential improvements include further tuning the model, exploring interaction effects between variables, and testing additional machine learning models to enhance prediction accuracy.
