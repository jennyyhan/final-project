# Predicting COVID-19 Mortality Using Patient Demographic and Clinical Data

This repository contains my BME 2310 final project. The goal of this project was to explore whether demographic and clinical variables could be used to predict mortality among confirmed COVID-19 patients.

## Research Question
Can demographic and clinical factors be used to predict mortality among confirmed COVID-19 patients?

## Methods
This project included:
- filtering the dataset to confirmed COVID-positive patients
- creating a binary mortality outcome variable
- cleaning coded missing values
- recoding binary predictor variables
- exploratory data analysis
- model training and comparison using Logistic Regression and Linear SVM

## Files
- Final Project Notebook.ipynb — main analysis notebook on Jupyter
- data_sample.csv — representative sample of the data used in the project

## Main Findings
- Age and major comorbidities were strongly associated with mortality
- Logistic Regression performed slightly better than Linear SVM
- Logistic Regression was also interpretable through feature coefficients
