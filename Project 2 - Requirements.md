Project 2: Missing Data Visualization and Imputation

Course: MSDS 515

1. Project Overview

Students will be provided with two datasets:

“Insertion_Depth_Dataset_missing_values.csv” which contains missing values in selected variables.
“Insertion_Depth_Dataset.csv” which contains the complete version of the same data for comparison purposes.
Through this project, students will visualize missing patterns, apply various imputation methods, and evaluate the performance of each method against the true values in the complete dataset.

 
2. Learning Outcomes and Objectives

Upon completion of this project, students will be able to:

Identify and visualize missing data patterns using appropriate tools.
Apply multiple imputation techniques such as mean, KNN, and regression-based methods.
Interpret effectively through data visualization and analysis.
3. Tasks and Requirements

Step 1: Data Loading

Load both datasets (Insertion_Depth_Dataset_missing_values.csv and Insertion_Depth_Dataset_missing_values.csv) using pandas.
Step 2: Missing Data Visualization

Use the missingno library to visualize the missing data patterns.
Interpret the visualizations and describe which variables contain missing data and any observable relationships among them.
Step 3: Imputation Methods

Apply the following imputation techniques on the dataset containing missing values:

Mean Imputation
K-Nearest Neighbors (KNN) Imputation
Linear Regression Imputation:
Ensure that the imputed datasets are stored separately for comparison (e.g., df_imputed_mean, df_imputed_knn, and df_imputed_regression).

Step 4: Visualization and Analysis

Plot histograms or boxplots of variables before and after imputation to visualize distributional changes.
 

Deliverables

A Jupyter notebook (.ipynb)
PowerPoint Presentation
A report with plots, measurements and observations.
 

Grading Criteria

Correctness of Code (40%): Simulations are correctly implemented and reproducible.
Report (30%): A report with plots, measurements and observations.
Presentation (30%)
