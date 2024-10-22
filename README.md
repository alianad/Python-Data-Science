# Breast Cancer Tumor Classification

This project was developed during my time in the Python Data Science Program under Yayasan Peneraju. The aim of this project is to create a machine learning model to assist healthcare professionals in diagnosing breast cancer by accurately classifying tumors as either malignant or benign.

## Project Objective

The main objective is to develop a predictive model that can classify breast tumors based on characteristics of the cell nuclei. This can aid healthcare professionals in early detection, potentially improving treatment outcomes.

## Problem Statement

Breast cancer is a major health concern, and early detection is crucial for effective treatment. Traditional diagnostic methods can be subjective and time-consuming. The goal of this project is to build an automated classification system using machine learning, focusing on:

1. **Accuracy**: Reliable differentiation between malignant and benign tumors.
2. **Timeliness**: Faster diagnostic results.
3. **Healthcare Impact**: Supporting medical professionals with informed diagnostic tools.

## Dataset Overview

The dataset consists of features computed from a digitized image of a breast mass. Key information about the dataset:

- **Number of Samples**: 569
- **Number of Features**: 33
  - **ID**: A unique identifier for each sample.
  - **Diagnosis**: The target variable indicating 'M' (Malignant) or 'B' (Benign) tumors.
  - **Measurement Features**: 
    - `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`, etc.
    - Measurements are provided for mean, standard error (SE), and worst-case scenarios.
- **Missing Data**: One empty column, `Unnamed: 32`, which has no values and can be ignored.

## Project Steps

1. **Data Preprocessing**: Cleaned the dataset by handling missing values and normalizing features.
2. **Exploratory Data Analysis (EDA)**: Visualized data distributions, correlations, and feature importance to identify key attributes influencing the diagnosis.
3. **Model Development**: Developed and evaluated multiple machine learning models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
4. **Model Evaluation**: Selected the best model based on accuracy, precision, recall, and F1-score. Analyzed results with confusion matrices and ROC curves.
5. **Results & Conclusions**: Documented the findings, including the final model's performance and potential improvements.


## Results

- The final model achieved an accuracy of 96% (to be replaced with actual results) on the test set, making it a reliable tool for breast cancer diagnosis.
- Detailed performance metrics, visualizations, and the confusion matrix can be found in the notebook.

- Dataset Source
This dataset appears to be similar to the well-known Breast Cancer Wisconsin (Diagnostic) Dataset, which is often used for machine learning benchmarks in medical diagnostics. The dataset contains measurements that are crucial for identifying cancerous tumors, supporting early and accurate diagnosis.

## Future Work

Possible improvements include:
- Exploring additional machine learning algorithms.
- Fine-tuning hyperparameters for improved accuracy.
- Integrating deep learning techniques.
- Creating a web application for easier use by medical staff.

## License
This project is open-source and available under the MIT License.

## Acknowledgements
Thanks to Yayasan Peneraju for the opportunity to enhance my skills in data science. Special recognition goes to the instructors and mentors who provided guidance throughout the project.

