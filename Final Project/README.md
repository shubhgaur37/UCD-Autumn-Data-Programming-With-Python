# Final Project - Data Programming with Python

## Overview
This directory contains the final project for the "Data Programming with Python" module, focusing on analyzing data derived from a study on performances of Portuguese students in math exams. This project includes tasks such as data loading, exploratory data analysis, statistical tests, regression, and clustering.

## Assignment Details
- **Objective**: Apply Python programming skills to analyze student performance data.
- **Data Source**: UCI Machine Learning Repository (https://doi.org/10.24432/C5TG7T)

## Assignment Questions

### 1. Data Analysis of Male Students
- **Task**:
  - Load the `male_stud.csv` dataset into Python as a pandas DataFrame.
  - Inspect the data. Determine the number of students and indicators, and check for missing values.
  - Perform an exploratory data analysis, creating numerical and graphical summaries. Discuss and interpret the results.

### 2. Data Analysis of Female Students
- **Task**:
  - Load the `female_stud.csv` dataset into Python as a pandas DataFrame.
  - Inspect the data. Determine the number of students and compare indicators with the male group.
  - Perform a t-test for each measurement to test for differences between male and female groups at a significance level of α = 0.01. Display t-scores and p-values, and explain the conclusions.

### 3. Correlation Analysis
- **Task**:
  - Combine the male and female datasets into a single DataFrame.
  - Compute the Pearson correlation coefficient between each measurement and identify the most correlated indicators. List the four most strongly correlated pairs.
  - Create scatter plots for each of the correlated pairs and interpret the relationships.

### 4. Logistic Regression for Predicting Student Failure
- **Task**:
  - Create a new column indicating whether the student passed or failed based on their final grade.
  - Separate the data into response and predictor variables and standardize the predictors.
  - Fit a logistic regression model and interpret the results.
  - Perform forward selection using the Akaike Information Criterion (AIC) and compare the selected model to the initial model.

### 5. Random Forest Regression for Predicting Final Grades
- **Task**:
  - Split the data into training and test sets.
  - Fit a random forest regression model with 10 trees using the training data. Identify the most important variables.
  - Use the model to predict final grades and create a scatter plot of true vs. predicted grades. Interpret the plot.
  - Assess the model's performance with different numbers of trees (5, 10, 50, 100, 500, 1000, 5000) by fitting the model 20 times with different random states. Plot the performance metrics and discuss the findings.
  - Explain the rationale for fitting the model multiple times with different random states.

### 6. Clustering Analysis to Identify Student Groups
- **Task**:
  - Perform a k-means cluster analysis using different numbers of clusters (1 to 10). Plot the performance and identify the optimal number of clusters.
  - Perform k-means clustering with the optimal number of clusters and identify the most discriminatory variables.
  - Create scatter plots for the most discriminatory variables, colored by cluster number, and discuss the findings.
  - Identify another suitable clustering algorithm, provide an overview, and repeat parts (a)–(c) using the chosen algorithm. Discuss the results in relation to the k-means clustering.

## Solutions
The complete solution to this assignment is available as an HTML document. You can view the solution by visiting the following link:

**[View Solution](https://shubhgaur37.github.io/UCD-Autumn-Data-Programming-With-Python/Final%20Project/Solution.html)**

## How to Use This Repository
- The `Solution.html` file in this directory contains the solutions to the final project.
- The assignment questions are detailed above and can be further reviewed in the linked solution.
