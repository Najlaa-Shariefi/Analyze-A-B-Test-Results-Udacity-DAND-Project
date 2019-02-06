# Analyze A/B Test Results
This project was completed as part of the course requirements of Udacity's [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) certification.

## Overview
The project conducted A/B testing of user conversions on an old and new wepage. 

Steps included handling mismatched condition and page assignment, removing duplicate ids, hypothesis testing via bootstrapping and standard statistical tests, and multiple regression modelling. 

## Statistical Analysis
- [Bootstrapping sampling distributions](https://rebeccaebarnes.github.io/2018/04/29/bootstrapping) and p-value calculations
- Z-core tests
- Logistic regression
- Multiple linear regression modelling to assess for interactions of independent variables

## Technologies Used
- Python, Numpy, Pandas, Matplotlib, StatsModels, Scipy
- LaTex
- Jupyter Notebook

## Key Findings
- The conversion rate for the new page was not superior to that for the old page 
- The country of the user did not impact the rate of conversion between the new and old page 

## Files
- Analyze_ab_test_results_notebook.ipynb: Code for A/B Testing and Analyzing this A/B Test Results.
- Analyze_ab_test_results_notebook.html: The html copy of the project.
- ab_data.csv: The orgignal dataset provided by Udacity , upon which A/B testing will be conducted.
- countries.csv: The additional dataset provided by Udacity.
