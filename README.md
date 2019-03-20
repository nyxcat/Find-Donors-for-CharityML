# Find-Donors-for-CharityML


### Introduction
This project employs several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. The best candidate algorithm is random forest classifier, which yields highest F-socre on the testing set time efficienctly. The F-\beta(\beta=0.5) score is chosen as the evaluation metric, since there are much more people who do not make more than $50,000 than people who makes more than $50,000.

The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The data contains information, such as age, education level, income and etc.


### Data Processing 
1. Transforming skewed continuous features
2. One-hot encoding categorical features


### Requirement
- python
- pandas
- numpy
- scikit-learn
- matplotlib

