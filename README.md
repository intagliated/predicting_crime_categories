# Predicting Crime Categories Using Machine Learning

## Project Overview
This project focuses on crime classification using machine learning models. The dataset comprises 20,000 records and 20 columns, covering aspects such as incident location, victim demographics, date, and time. The target variable includes six crime categories:

## Data Exploration, Cleaning, and Preprocessing
- Conducted thorough data exploration to understand patterns and missing values.
- Created 23 relevant feature columns to enhance model performance.

## Machine Learning Models
Two models were utilized for classification:

- **LGBMClassifier**
- **XGBoostClassifier**

A **VotingClassifier** was built using these two classifiers, leading to an improved accuracy of **0.88080**, significantly higher than the baseline accuracy of approximately **0.58**.

