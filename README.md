# Salary Prediction Using Simple Linear Regression

This project predicts employee salary from years of experience using a simple linear regression model.

## Project Overview

The notebook demonstrates a beginner-friendly machine learning workflow:

- Load and inspect a salary dataset
- Visualize the relationship between experience and salary
- Train a simple linear regression model
- Evaluate prediction performance
- Predict salary for new experience values

## Project Structure

```text
Salary_Prediction_Simple_Regression/
|-- Salary_dataset.csv
|-- Simple_Regression.ipynb
|-- requirements.txt
`-- README.md
```

## Dataset

The dataset contains:

| Column | Description |
|---|---|
| YearsExperience | Employee experience in years |
| Salary | Employee salary |

## Tech Stack

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook Simple_Regression.ipynb
```

## Key Learning

Simple linear regression is useful when the target variable changes approximately linearly with one input feature. In this project, years of experience is used to estimate salary.
