# Data Visualization and Classification on Titanic Dataset

In this project, I did an in-depth analysis and visualization of the titanic dataset which can be found on [Kaggle](https://www.kaggle.com/c/titanic/data). The goal of the project is to understand the relationship between characteristic features of titanic passengers and their survival rate, and train various classification models to predict the survival rate.

## Results

Predicted data was checked on Kaggle and models had the following scores (a score of 0.77 means 77% of the passengers were correctly predicted):

- Logistic Regression : 0.77
- K-Nearest Neighbors : 0.67
- Support Vector Machine : 0.77
- Decision Tree : 0.73
- Random Forest : 0.75

## Data Visualization

For data visualization, [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/index.html) libraries are used to understand the impact of the following features on a passenger's survival rate:

- Age
- Sex
- Pclass (Ticket class)
- Port of Embarkation
- Number of family members on board (siblings & spouses)

## Logistic Regression

[NumPy](https://numpy.org/) and [scikit-learn](https://scikit-learn.org/stable/) are used to train different classification models.

## Requirements

- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/)
