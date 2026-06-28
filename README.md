# Sleep Health Statistical Learning

## Overview

I built this project for my Statistical Learning course at Indiana University Indianapolis.

The goal was to see if lifestyle and health information could accurately predict whether someone had no sleep disorder, insomnia, or sleep apnea. We also wanted to figure out which health factors were the strongest indicators of sleep disorders instead of only focusing on prediction accuracy.

Using the Sleep Health and Lifestyle Dataset from Kaggle, we cleaned the data, explored relationships between variables, built several machine learning models, and compared their performance.

---

## What We Looked At

Some of the variables included:

- Age
- BMI
- Blood Pressure
- Daily Steps
- Physical Activity
- Stress Level
- Sleep Duration
- Sleep Quality
- Heart Rate
- Occupation

Before modeling, we cleaned the dataset by handling missing values, splitting blood pressure into systolic and diastolic measurements, encoding categorical variables, and scaling the data where needed.

---

## Models Compared

We compared three different machine learning approaches:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

Each model had a different purpose.

Logistic Regression gave us an interpretable baseline, KNN grouped together similar health profiles, and Random Forest handled more complex relationships between variables.

---

## Results

Random Forest produced the best overall performance with about 97% accuracy while using only a small number of important features.

Some of the biggest takeaways were:

- BMI was one of the strongest predictors of Sleep Apnea.
- Stress Level and Sleep Quality were highly correlated.
- Random Forest handled the nonlinear relationships better than the other models.
- Logistic Regression was slightly less accurate but much easier to interpret.
- KNN still performed well after feature scaling and hyperparameter tuning.

---

## Repository Contents

- **Sleep_Health_Statistical_Learning.ipynb** – Complete notebook including data cleaning, EDA, feature engineering, model training, and evaluation.
- **report/final_project_written_report.pdf** – Final written report.
- **presentation/final_project_presentation.pdf** – Final class presentation.
- **data/README.md** – Information about the dataset.

---

## Skills Demonstrated

- Python
- Pandas
- NumPy
- Scikit-learn
- Data cleaning
- Exploratory data analysis
- Feature engineering
- Classification
- Logistic Regression
- K-Nearest Neighbors
- Random Forest
- Hyperparameter tuning
- Cross-validation
- Model evaluation
- Statistical inference
- Data visualization

---

## Why I'm Including This Project

I'm including this project because it demonstrates the complete machine learning workflow—from preparing raw data to comparing models, evaluating performance, and interpreting the results. It highlights many of the core data science skills I've developed throughout my coursework.
