#Weight Lifting Exercise Prediction Project
##Overview

This project aims to predict the manner in which participants performed weight lifting exercises using data collected from accelerometers on the belt, forearm, arm, and dumbbell. The main goal is to predict the classe variable in the training dataset, representing different types of exercise execution.

The analysis uses machine learning techniques and explores model selection, cross-validation, and prediction performance. The results are applied to a test dataset to generate predictions for evaluation.

Files in this Repository

Weight_Lifting_Exercise_Prediction.Rmd – R Markdown file containing the full analysis, code, and explanations.

Weight_Lifting_Exercise_Prediction.html – Compiled HTML version of the report for easy viewing.

Weight_Lifting_Exercise_Prediction.pdf – PDF version of the report (optional).

README.md – This file.

##Data

Training data: pml-training.csv

Test data: pml-testing.csv

The datasets were collected from wearable accelerometers during barbell lifts.

##Analysis

Data Cleaning: Removal of near-zero variance predictors and columns with missing values.

Exploratory Data Analysis: Summary statistics and plots to understand the features.

##Modeling:

Random Forest was used to predict the classe variable.

5-fold cross-validation was employed for model tuning.

Prediction: The model was applied to 20 test cases to generate predictions.

##How to Reproduce

Download all files in this repository.

Open Weight_Lifting_Exercise_Prediction.Rmd in RStudio.

Knit the R Markdown file to HTML or PDF.

Ensure required packages are installed: caret, randomForest, ggplot2.

###Author

Medini Jeere
