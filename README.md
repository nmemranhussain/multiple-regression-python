# Multiple Regression Model for Health Premium Prediction

This repository contains a multiple regression analysis developed as part of the DNSC 6303 - Programming for Analytics I course at George Washington University. The project builds and evaluates a predictive model for health insurance premiums based on various health and demographic factors.

## Model Overview

The multiple regression model predicts **health premium costs** (dependent variable) using the following independent variables:
- **Patient Age**
- **Diabetes Diagnosis**
- **Blood Pressure Problem**
- **Transplant History**
- **Chronic Disease Presence**
- **Patient Weight**
- **Patient Height**
- **Known Allergies**

### Dataset

The dataset used for this analysis is `payor.csv`, which includes anonymized patient data and is derived from an initial quiz dataset. Key variables include the patient’s age, weight, height, and known medical conditions.

### Objective

The primary aim of this project is to:
1. Load and preprocess the dataset.
2. Build a multiple regression model.
3. Analyze model diagnostics.
4. Assess the impact of each variable on health premium costs.
5. Provide insights and recommendations based on the results.

### Methodology

- **Data Preprocessing**: Data was split into 80% training and 20% test datasets.
- **Model Fitting**: Using Python libraries to estimate model parameters.
- **Diagnostics**: Residual analysis and QQ plots for model validation.
- **Model Evaluation**: R-squared and residual distribution analysis to evaluate fit.

### Key Findings

- **Significant Variables**: Age, Transplants, Chronic Diseases, and Weight have the most significant impact on health premiums.
- **Insignificant Variables**: Blood Pressure Problems, Height, and Known Allergies showed no significant effect.
- **Model Performance**: The model achieved an R-squared value of 0.694, explaining 69.4% of the variance in premium costs.

### Conclusion

This analysis identifies critical health and demographic factors that impact health premium costs, providing insights for insurance premium modeling. While the model fits reasonably well, some variables remain statistically insignificant, highlighting areas for further refinement and exploration.

### Repository Structure

- `6303_project.ipynb`: Jupyter Notebook containing the full analysis and model development.
- `payor.csv`: Dataset used in the analysis.

### License

This project is shared under the [appropriate license of choice, e.g., MIT License].

---

Feel free to modify or extend this README as per your project’s needs!
