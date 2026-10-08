# SWYNEX Exploratory Data Analysis – Titanic Dataset

## Project Overview

This project was completed as part of the SWYNEX Technologies Data Science Internship.

The objective of this task was to perform Exploratory Data Analysis (EDA) on the prepared Titanic dataset and identify important patterns and insights that can support further machine learning and decision-making.

## Dataset

The Titanic dataset contains information about passengers, including:

- Passenger Class
- Age
- Sex
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket
- Fare
- Embarked Port
- Survival Status

## EDA Performed

The following analysis was performed:

1. Dataset shape and basic information
2. Descriptive statistics
3. Survival distribution
4. Survival rate by gender
5. Survival rate by passenger class
6. Age distribution
7. Fare distribution
8. Correlation analysis using a heatmap

## Key Insights

### 1. Overall Survival
Approximately 38.4% of passengers survived, meaning the majority of passengers did not survive.

### 2. Gender and Survival
Female passengers had a substantially higher survival rate than male passengers. Therefore, Sex can be an important feature for predicting survival.

### 3. Passenger Class and Survival
First-class passengers had a higher survival rate, while third-class passengers had a much lower survival rate. Pclass can therefore be an important predictive feature.

### 4. Age Distribution
Passenger ages ranged from children to older adults, with an average age of approximately 29.4 years. Age may provide useful information for predicting survival.

### 5. Fare Distribution
Most passengers paid relatively low fares, while a small number paid very high fares. Fare may provide useful information for predicting survival.

### 6. Feature Relationships
Correlation analysis showed relationships among numerical variables such as Survived, Pclass, Age, SibSp, Parch, and Fare. These relationships can help identify potentially useful features for further modeling.

## Conclusion

Exploratory Data Analysis helped identify important patterns in the Titanic dataset. Gender, passenger class, age, and fare showed useful relationships with survival.

These findings can guide feature selection and help build a machine learning model in the next stage.

## Files

- `SWYNEX_Exploratory_Data_Analysis.ipynb` – EDA notebook containing the analysis, statistics, visualizations, and insights.
- `SWYNEX_Titanic_Cleaned.csv` – Cleaned Titanic dataset used for the analysis.

## Internship

This project was completed as part of the **SWYNEX Technologies Data Science Internship**.
