# Predicting University Student Dropout

**Early Academic Indicators, Predictive Modeling, and Intervention Decisions**

## Project Overview

Can universities identify students at risk of dropping out using information collected during their first semester? More importantly, can those predictions help institutions make better decisions about student support?

This project examines 4,424 student records, using exploratory analysis and logistic regression to investigate three first-semester academic indicators: curricular units approved, average grades, and evaluations. The predictive model uses 3,630 records with known graduation or dropout outcomes.

The analysis explores the tradeoff between identifying students who may drop out and generating false alarms that require institutional resources.

## Research Report

**Early Signals of Student Dropout: Finding the Line Between Detection and False Alarms**

[Read the full research report (PDF)](student_dropout_research_report.pdf)

The report presents the research question, methodology, predictive modeling results, classification threshold analysis, limitations, and implications for institutional decision-making.

## Executive Presentation

[Watch the 5-minute research presentation on YouTube](https://youtu.be/h4_rZCiSh_c)

## Key Findings

- A logistic regression model achieved approximately 83% classification accuracy on the test dataset.
- Lowering the classification threshold from 50% to 40% identified 16 additional students who eventually dropped out, while generating 19 additional false positives.
- Predictive accuracy alone is insufficient to establish whether an intervention improves student retention.
- The 40% threshold was explored using the test data and therefore requires independent validation before being recommended for institutional use.

## Methods and Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, exploratory data analysis, logistic regression, and classification threshold analysis.

## Python Notebook

[View the complete Python analysis](student_dropout_prediction.ipynb)

## Reproducing the Analysis

1. Download the dataset from the [UCI Machine Learning Repository](https://doi.org/10.24432/C5MC89).
2. Open `student_dropout_prediction.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required Python libraries: pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.
4. Update the dataset file path if necessary, then run the notebook from beginning to end.

The analysis uses an 80/20 stratified training/test split with a random seed of 42. Classification thresholds of 50%, 40%, 30%, and 20% are examined.

## Data Source

[Predict Students' Dropout and Academic Success — UCI Machine Learning Repository](https://doi.org/10.24432/C5MC89)

## Research Implications

The findings support further evaluation of early-warning systems through small-scale pilot programs that measure predictive performance, advising workload, and actual student retention outcomes.

A central distinction is that predicting student dropout does not establish that an intervention will prevent it.

## Author

Timothy J. Xeriland

Quantitative Research | Statistics | Artificial Intelligence | Python & Data Analytics
