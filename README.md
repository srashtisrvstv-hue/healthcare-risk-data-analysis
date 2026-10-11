# Healthcare Risk Data Analysis

## Project Overview
This project explores health-related data and builds machine learning models to predict diabetes status.

## Dataset
The dataset contains 100,000 records and nine columns, including age, gender, hypertension, heart disease, smoking history, BMI, HbA1c level, blood glucose level, and diabetes status.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and explore the dataset.
2. Check for missing values and remove duplicate records.
3. Perform exploratory data analysis and create visualizations.
4. Encode categorical variables.
5. Split the data into training and testing sets.
6. Train Logistic Regression and Balanced Logistic Regression models.
7. Compare model performance.

## Model Results

| Metric | Logistic Regression | Balanced Logistic Regression |
|---|---:|---:|
| Accuracy | 96.0% | 88.5% |
| Precision | 86.9% | 42.5% |
| Recall | 63.9% | 88.0% |
| F1-score | 73.6% | 57.4% |

## Key Findings
The standard model achieved higher accuracy, while the balanced model detected a greater proportion of actual positive cases. This illustrates the trade-off between accuracy, precision, and recall.

## Disclaimer
This project is for educational purposes only and is not intended for medical diagnosis.
