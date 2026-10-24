# Predicting Student Depression from Academic & Lifestyle Factors

## Overview
This project explores how accurately we can predict student depression from academic and lifestyle factors from a public survey dataset.

## Data
A public student survey dataset from [Kaggle](https://www.kaggle.com/datasets/ikynahidwin/depression-student-dataset) of 502 students, with nearly equal numbers reporting depression and not. Variables: sex, age, academic pressure, study satisfaction, sleep duration, dietary habits, suicidal thoughts, study hours, financial stress, history of mental illness, and self-reported depression.

## Methods
* Cleaned and wrangled dataset
* EDA on each variable’s relationship with depression
* Random forest classifier model
  * Evaluated with a confusion matrix and AUC

* **Tools:** tidyverse, tidymodels, ggplot2, randomForest, caret, pROC, ROSE

## Key Findings
The model predicted student depression with about 88.7% accuracy on the test set. Academic pressure, suicidal thoughts, and financial stress ranked among the most important predictors.

## Files
- `data/` - data folder
  - `student_depression.csv`: student depression csv from Kaggle
- `student_depression.Rmd`: R Markdown file with the full code and analysis
- `student_depression.html`: rendered report


## Team
Group project by Roxana Chen, Jiayi Xue, Sehee Kim, Jorge Ramos, Nick Liu
