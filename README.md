# Stackoverflow-survey_analyse

## Libraries
- pandas
- numpy
- matplotlib
- seaborn

## Background
Based on data provided by StackOverflow(2020), this project analyzed the factors that Internet professionals (surveyed) value in choosing a career, their frequency of overtime work, and their preferred programming language.

Data source: https://insights.stackoverflow.com/survey

## Main Steps
1. Clean data

For some multiple choice questions, multiple responses selected by a respondent are fused and stored together in the provided documentation. This makes it impossible to directly analyze the frequency of occurrence of each option.
Therefore, we first need to clean up this type of data. This step is mainly applied to check the data distribution of the questions "commonly considered career selection factors" and "frequency of overtime work in different industries".
