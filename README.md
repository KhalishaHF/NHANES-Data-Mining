# NHANES-Data-Mining

# Overview
This project explores the relationship between diabetes status and various health, dietary, and demographic factors using data from the NHANES (National Health and Nutrition Examination Survey).
It involves a complete end-to-end data analysis pipeline from data cleaning and visualisation to statistical testing and machine learning modelling.

# Objectives
- Identify key variables correlated with diabetes occurrence.
- Explore health indicators such as BMI, waist circumference, and glycohemoglobin.
- Build a predictive model for diabetes classification.
- Maintain ethical and privacy awareness when working with health data.

# Tools & Libraries
- Python (Pandas, NumPy, SciPy, Statsmodels, Scikit-learn)
- Data Visualisation: Matplotlib, Seaborn, and Bokeh (for interactive plots)
- Machine Learning: Random Forest Classifier, SMOTE for class balancing
- Statistical Analysis: t-tests for significance testing

# Data Preparation
- Merged datasets from 2017–2023 (Demographics, Diet, Examination, Glycohemoglobin, and Diabetes files).
- Handled missing values with SimpleImputer (mean strategy).
- Removed duplicates and unnecessary columns (e.g., Education_Level).
- Verified integrity and performed scaling using StandardScaler.

# Exploratory Data Analysis (EDA)
Visualisations:
- BMI distribution (histogram + interactive slider)
- Diabetes prevalence (bar chart)
- BMI and glycohemoglobin distributions by diabetes diagnosis
- Correlation heatmap of continuous features
- Parallel coordinates for multivariate comparison
Statistical Findings:
BMI, Glycohemoglobin, and Waist Circumference show significant differences (p < 0.05) between diabetic and non-diabetic groups.

# Machine Learning Model
Model: Random Forest Classifier
Accuracy: 91.23%
Key Metrics:
Precision (Diabetic): 0.69, Recall (Diabetic): 0.72, F1-score (Diabetic): 0.71
These results indicate reliable performance in classifying diabetes status using selected health indicators.

