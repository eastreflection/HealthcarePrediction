# HealthcarePrediction
 Building a model with high accuracy to predict whether patients in the dataset have diabetes
# Healthcare Project: Diabetes Prediction

## Overview
This project aims to build a predictive model to diagnose diabetes in patients based on specific diagnostic measurements. The dataset used originates from the National Institute of Diabetes and Digestive and Kidney Diseases and focuses on female patients aged at least 21 years of Pima Indian heritage.

## Problem Statement
The primary objective is to develop a model with high accuracy to predict whether patients in the dataset have diabetes, utilizing various medical predictor variables.

## Dataset Description
The dataset consists of 768 instances and includes the following features:

### Predictor Variables
1. **Pregnancies**: Number of times pregnant
2. **Glucose**: Plasma glucose concentration at 2 hours in an oral glucose tolerance test
3. **BloodPressure**: Diastolic blood pressure (mm Hg)
4. **SkinThickness**: Triceps skinfold thickness (mm)
5. **Insulin**: 2-Hour serum insulin (mu U/ml)
6. **BMI**: Body mass index (weight in kg/(height in m)^2)
7. **DiabetesPedigreeFunction**: Diabetes pedigree function
8. **Age**: Age in years

### Target Variable
- **Outcome**: Class variable (0 or 1) indicating the presence (1) or absence (0) of diabetes. The dataset contains 268 instances labeled as 1 (indicating diabetes) and 500 labeled as 0.

## Data Preprocessing
- **Handling Missing Values**: The dataset treats 0 values as nulls and replaces them with the mean of their respective feature columns.
- **Outlier Detection and Treatment**: Outliers are identified and treated using the Interquartile Range (IQR) method to ensure the integrity of the dataset.

## Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Histograms and violin plots are used to visualize the distribution of features.
- **Bivariate Analysis**: Scatter plots are created to understand relationships between variables.
- **Correlation Analysis**: A heatmap is generated to visualize correlations among features.

## Model Building
Various machine learning algorithms are considered for building the predictive model, including:
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machine (SVC)
- K-Nearest Neighbors (KNN)
- Naive Bayes

## Evaluation Metrics
The model's performance will be evaluated using metrics such as:
- Accuracy Score
- Precision
- Recall
- F1 Score
- ROC-AUC

## Future Work
- Address class imbalance in the dataset using techniques like resampling or SMOTE.
- Further tuning of model parameters to improve prediction accuracy.

## Conclusion
This project provides a valuable opportunity to develop a predictive model for diabetes based on demographic and health-related features. The findings from the analysis and modeling can potentially aid in early diagnosis and better management of diabetes in patients.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
