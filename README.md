# Symptom Matcher

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Random Forest Classifier](#random-forest-classifier)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Project Overview

The Symptom Matcher project utilizes a dataset containing symptoms and disease labels to build a predictive model using the Random Forest Classifier. This model helps predict the disease based on the provided symptoms.

### Primary Objectives

1. **Data Loading**: Load the dataset containing symptoms and disease labels.

2. **Exploratory Data Analysis (EDA)**: Perform basic data exploration to understand the dataset's structure and characteristics.

3. **Random Forest Classifier**: Build a predictive model using the Random Forest Classifier algorithm to predict diseases based on symptoms.

4. **User Interaction**: Allow users to input their symptoms and use the model to predict potential diseases.

## Dataset

The dataset used in this project contains the following columns:

- Symptoms: Various symptoms represented as Boolean values (0 or 1).
- Diseases: Labels representing different diseases.

## Exploratory Data Analysis

The exploratory data analysis (EDA) phase includes examining basic statistics of the dataset and understanding the distribution of symptoms and diseases.

## Random Forest Classifier

A Random Forest Classifier is employed to create a predictive model. The model is trained on the dataset, and its performance is evaluated using metrics such as F1-score, precision, recall, and accuracy.

## Usage

To use the Symptom Matcher:

1. Load the dataset containing symptoms and disease labels.
2. Perform EDA to understand the dataset.
3. Train a Random Forest Classifier on the dataset.
4. Allow users to input their symptoms.
5. Use the trained model to predict potential diseases based on the provided symptoms.

## Conclusion

The Symptom Matcher project provides a tool for predicting diseases based on symptoms using a Random Forest Classifier. Users can interact with the model by entering their symptoms to get potential disease predictions