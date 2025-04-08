# AI-ML-Employee-Satisfaction-Survey-Data-Prediction

## Summary (obtained from Kaggle): 
The Employee Satisfaction Survey dataset is a comprehensive collection of information regarding employees within a company. It includes essential details such as employee identification numbers, self-reported satisfaction levels, performance evaluations, project involvement, work hours, tenure with the company, work accidents, promotions received in the last 5 years, departmental affiliations, and salary levels. This dataset offers valuable insights into the factors influencing employee satisfaction and can be used to analyze and understand various aspects of the workplace environment.


## Data: 
Data is obtained from Kaggle:
https://www.kaggle.com/datasets/redpen12/employees-satisfaction-analysis/data

## Methods of observation: 
This project contains data cleaning methods of removing and replacing null data and columns. It contains boxplots to observe spreads and outliers and identify any meaningful vs non-meaningful features. The dataset is correlated to identify relationships between features and employee satisfaction. Multiple regression models are then trained and tested on the dataset to find the best fit and the accuracy score. .

## Conclusion and Path Forward: 
In this analysis, we have visually determined outliers and characteristics of the dataset features, plotted correlations, and compared the performance of different regression models. We accurately determined that the Work accidents, promotions over the last five years, average montly hours at work, and the salary had minimal impacts in predicting satisfaction.

While training and testing the models, the highest R^2 accuracy score we have obtained is __32.5 percent__ for a ridge regression model with an α value of 0.1. In the future, we can use even more advanced regressors and classifiers such as decision tree and random forest algorithms to build an even more robust and accurate predictive model.
