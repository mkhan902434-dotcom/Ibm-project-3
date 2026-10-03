# Student Performance Analysis and Prediction using AI

## Project Overview

This project analyzes student academic and social information and uses
machine learning to estimate the final grade (G3).

## Objectives

-   Perform data cleaning and exploratory data analysis.
-   Identify relationships between student factors and final grade.
-   Build regression models for final-grade prediction.
-   Compare Linear Regression with Random Forest.
-   Interpret model feature importance.

## Dataset

UCI Machine Learning Repository --- Student Performance\
Dataset page:
https://archive.ics.uci.edu/dataset/320/student+performance

The UCI page reports 649 instances and describes the data as student
achievement information from two Portuguese schools. The dataset
includes demographic, social and school-related variables.

## AI/ML Approach

The project uses: - Linear Regression as a baseline. - Random Forest
Regressor as the main machine-learning model. - One-hot encoding for
categorical variables. - Standardization for numerical variables. - MAE,
RMSE and R² for evaluation. - Random Forest feature importance for
interpretation.

G1 and G2 are excluded from the prediction features so the project
focuses on information available before the final grade.

## Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, UCI ML
Repository, Jupyter Notebook.

## Setup

1.  Install Python 3.10 or later.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Open `YourName_Student_Performance_AI_Analytics.ipynb` in Jupyter
    Notebook or Google Colab.
4.  Run the notebook cells from top to bottom.
5.  Internet access is required when the notebook fetches the UCI
    dataset.

## Files

-   `YourName_Student_Performance_AI_Analytics.ipynb` --- complete
    project code
-   `requirements.txt` --- Python dependencies
-   `YourName_Student_Performance_AI_Analytics_ProjectReport.docx` ---
    project report
-   `README.md` --- project overview and setup instructions

## Disclaimer

This is an academic project. Predictions are model estimates and should
not be used as the sole basis for decisions about individual students.
