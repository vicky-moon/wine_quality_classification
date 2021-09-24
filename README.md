# Vine quality classification

This is a simple classification project. 

I've split target data into 3 classes of wine: Poor, Normal, Good.

The task is to classify wine quality into these three classes.


## Data
Dataset is taken from the Kaggle datasets: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009

This is a csv file.

There are 1599 rows and 12 features there.


## Methodology
Data visualization

Feature selection (checking for constant features)

Feature scaling

Cross-validation 


**Model**
I’ve tried several models:

Logistic Regression

RandomForestClassifier

KNeighborsClassifier

DecisionTreeClassifier

SVC

The highest F1 score was riched by RandomForestClassifier. f1=89 on validation set


## Technologies
Python

NumPy

pandas

sklearn

matplotlib
