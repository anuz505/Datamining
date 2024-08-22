# Heart Disease Prediction Project

This project focuses on building and evaluating different machine learning models to predict heart disease based on patient data. The dataset contains various features related to cardiovascular health, such as age, cholesterol levels, and maximum heart rate, which are used to train and evaluate models like K-Nearest Neighbors (KNN), Decision Trees, and Naive Bayes.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Models Used](#models-used)
- [Performance Metrics](#performance-metrics)
- [Visualizations](#visualizations)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
This project aims to classify whether a patient has heart disease based on several health-related features. Three machine learning algorithms are implemented to evaluate their performance in predicting heart disease: K-Nearest Neighbors (KNN), Decision Tree, and Naive Bayes.

## Dataset
The dataset used in this project is the [Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) from the UCI Machine Learning Repository. It consists of 14 features including age, sex, chest pain type, resting blood pressure, serum cholesterol, and more.

## Features
- **Age**: Age of the patient.
- **Sex**: Gender of the patient (1 = male; 0 = female).
- **CP**: Chest pain type (4 values).
- **Trestbps**: Resting blood pressure (in mm Hg).
- **Chol**: Serum cholesterol in mg/dl.
- **Fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
- **Restecg**: Resting electrocardiographic results.
- **Thalach**: Maximum heart rate achieved.
- **Exang**: Exercise induced angina (1 = yes; 0 = no).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: The slope of the peak exercise ST segment.
- **Ca**: Number of major vessels (0-3) colored by fluoroscopy.
- **Thal**: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect).
- **Target**: Heart disease status (1 = disease; 0 = no disease).

## Models Used
1. **K-Nearest Neighbors (KNN)**:
   - A simple algorithm that classifies a data point based on the majority vote of its neighbors.
   - Hyperparameters: K = 5.
   
2. **Decision Tree**:
   - A tree-like model used for classification and regression by splitting the data into subsets based on feature values.
   
3. **Naive Bayes**:
   - A probabilistic classifier based on Bayes' theorem with strong independence assumptions between the features.

## Performance Metrics
The following performance metrics were calculated for each model:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## Visualizations
The project includes visualizations for exploratory data analysis and performance metrics, such as:
- Scatter plots and regression lines for age vs. other health metrics.
- Heatmap of the correlation matrix.
- Distribution plots for each feature.
- Performance metrics comparison for each model.

## Installation
To run this project, you need to have R and the following libraries installed:
```r
install.packages(c("e1071", "ggplot2", "gridExtra", "reshape2", "caret", "class", "rpart"))
