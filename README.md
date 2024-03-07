## Scholastic Performance Review

## Life cycle of Machine learning Project

- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- Exploratory data analysis
- Data Pre-Processing
- Model Training
- Choose best model

## Problem statement
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course

## Run from terminal:

docker build -t testdocker.azurecr.io/mltest:latest .

docker login testdocker.azurecr.io

docker push testdocker.azurecr.io/mltest:latest
