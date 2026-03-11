# Classifying Shooting Incident Fatality Using Machine Learning

## Project Overview
This project focuses on analyzing historical shooting incident data to classify whether a shooting incident results in a fatal or non-fatal outcome. The objective is to support data-driven public safety strategies by identifying patterns associated with fatal incidents.

The project applies a complete data science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, statistical validation, and machine learning model development.

## Problem Statement
Shooting incidents represent a significant public safety challenge. Understanding the conditions that increase the likelihood of fatal outcomes can help law enforcement agencies develop targeted policing strategies and improve emergency response planning.

This project aims to develop a machine learning model capable of predicting whether a shooting incident will result in a fatality based on historical data.

## Dataset
Dataset used: **NYPD Shooting Incident Data (Historic)**

The dataset contains information about shooting incidents including:

- Incident date and time
- Borough and precinct
- Victim demographics
- Perpetrator demographics
- Geographic coordinates
- Fatality indicator

Target variable:

`STATISTICAL_MURDER_FLAG`

- True → Fatal incident  
- False → Non-fatal incident

## Project Workflow

### 1. Data Understanding
Initial exploration of the dataset including structure, data types, and feature descriptions.

### 2. Data Preprocessing
- Missing value analysis
- Unique value analysis
- Duplicate data check
- Data cleaning and column removal
- Data type conversions

### 3. Feature Engineering
Temporal and contextual features were created including:

- YEAR
- MONTH
- DAY_OF_WEEK
- HOUR
- IS_NIGHT
- IS_WEEKEND
- IS_SUMMER
- NIGHT_WEEKEND interaction

### 4. Exploratory Data Analysis
EDA was conducted to identify patterns across:

- Temporal trends
- Victim demographics
- Perpetrator demographics
- Geographic distribution of incidents

### 5. Statistical Validation
Statistical techniques were used to validate relationships between features and the target variable.

- Correlation Analysis
- Chi-Square Test

### 6. Feature Encoding
Two encoding techniques were used:

High Cardinality Encoding
- Frequency encoding for location features

Low Cardinality Encoding
- One-hot encoding for demographic attributes

### 7. Model Development
Multiple machine learning models were implemented and compared:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

### 8. Handling Class Imbalance
Two strategies were evaluated:

- Class weight adjustment
- SMOTE resampling

### 9. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Cross-validation was used to ensure reliable performance estimation.

### 10. Final Model
The **XGBoost Classifier** demonstrated the best overall performance and was selected as the final model.

## Key Insights
- Shooting incidents show identifiable temporal patterns.
- Certain locations exhibit higher incident concentration.
- Demographic and contextual features influence fatality risk.

These insights can support targeted policing strategies and resource allocation decisions.

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
XGBoost  
Matplotlib  
Seaborn  
Power BI  

## Project Files
# Classifying Shooting Incident Fatality Using Machine Learning

## Project Overview
This project focuses on analyzing historical shooting incident data to classify whether a shooting incident results in a fatal or non-fatal outcome. The objective is to support data-driven public safety strategies by identifying patterns associated with fatal incidents.

The project applies a complete data science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, statistical validation, and machine learning model development.

## Problem Statement
Shooting incidents represent a significant public safety challenge. Understanding the conditions that increase the likelihood of fatal outcomes can help law enforcement agencies develop targeted policing strategies and improve emergency response planning.

This project aims to develop a machine learning model capable of predicting whether a shooting incident will result in a fatality based on historical data.

## Dataset
Dataset used: **NYPD Shooting Incident Data (Historic)**

The dataset contains information about shooting incidents including:

- Incident date and time
- Borough and precinct
- Victim demographics
- Perpetrator demographics
- Geographic coordinates
- Fatality indicator

Target variable:

`STATISTICAL_MURDER_FLAG`

- True → Fatal incident  
- False → Non-fatal incident

## Project Workflow

### 1. Data Understanding
Initial exploration of the dataset including structure, data types, and feature descriptions.

### 2. Data Preprocessing
- Missing value analysis
- Unique value analysis
- Duplicate data check
- Data cleaning and column removal
- Data type conversions

### 3. Feature Engineering
Temporal and contextual features were created including:

- YEAR
- MONTH
- DAY_OF_WEEK
- HOUR
- IS_NIGHT
- IS_WEEKEND
- IS_SUMMER
- NIGHT_WEEKEND interaction

### 4. Exploratory Data Analysis
EDA was conducted to identify patterns across:

- Temporal trends
- Victim demographics
- Perpetrator demographics
- Geographic distribution of incidents

### 5. Statistical Validation
Statistical techniques were used to validate relationships between features and the target variable.

- Correlation Analysis
- Chi-Square Test

### 6. Feature Encoding
Two encoding techniques were used:

High Cardinality Encoding
- Frequency encoding for location features

Low Cardinality Encoding
- One-hot encoding for demographic attributes

### 7. Model Development
Multiple machine learning models were implemented and compared:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

### 8. Handling Class Imbalance
Two strategies were evaluated:

- Class weight adjustment
- SMOTE resampling

### 9. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Cross-validation was used to ensure reliable performance estimation.

### 10. Final Model
The **XGBoost Classifier** demonstrated the best overall performance and was selected as the final model.

## Key Insights
- Shooting incidents show identifiable temporal patterns.
- Certain locations exhibit higher incident concentration.
- Demographic and contextual features influence fatality risk.

These insights can support targeted policing strategies and resource allocation decisions.

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
XGBoost  
Matplotlib  
Seaborn  
Power BI  

## Project Files
EDA_and_Preprocessing.ipynb
Feature_Engineering_and_Model_Comparison.ipynb
Final_Model_XGBoost.ipynb
Project_Report.pdf


## Future Improvements
- Integrate socioeconomic and environmental datasets
- Apply advanced interpretability techniques such as SHAP
- Develop real-time prediction systems for public safety monitoring

## Author

Illuri Sunil Kumar Reddy
