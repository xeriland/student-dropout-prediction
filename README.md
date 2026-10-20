# Predicting University Student Dropout

**Early Academic Indicators, Predictive Modeling, and Intervention Decisions**

## Project Overview

Can universities identify students at risk of dropping out using information collected during their first semester? More importantly, can those predictions help institutions make better decisions about student support?

This project examines 4,424 student records using Python and logistic regression, focusing on three academic indicators: curricular units completed, average grades, and evaluations.

The analysis explores the tradeoff between identifying students who may drop out and generating false alarms that require institutional resources.

## Executive Presentation

[Watch the 5-minute research presentation on YouTube](https://youtu.be/h4_rZCiSh_c)

## Research Report

**Early Signals of Student Dropout: Finding the Line Between Detection and False Alarms**

[Read the full research report (PDF)](student_dropout_report.pdf)

The report presents the research question, methodology, predictive modeling results, classification threshold analysis, limitations, and implications for institutional decision-making.

## Key Findings

- A logistic regression model achieved approximately 83% classification accuracy on the test dataset.
- Lowering the classification threshold from 50% to 40% identified 16 additional students who eventually dropped out, while generating 19 additional false positives.
- Predictive accuracy alone is insufficient to establish whether an intervention improves student retention.

## Methods and Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, exploratory data analysis, logistic regression, and classification threshold analysis.

## Python Notebook

[View the complete Python analysis](student_dropout_prediction.ipynb)

## Data Source

UCI Machine Learning Repository — *Predict Students' Dropout and Academic Success*.

## Research Implications

The findings support further evaluation of early-warning systems through small-scale pilot programs that measure predictive performance, advising workload, and actual student retention outcomes.

A central distinction is that predicting student dropout does not establish that an intervention will prevent it.

## Author

Timothy J. Xeriland

Quantitative Research | Statistics | Artificial Intelligence | Python & Data Analytics
