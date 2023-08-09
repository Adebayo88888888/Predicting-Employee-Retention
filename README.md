# Predicting-Employee-Retention

Business Understanding:

As a data specialist working for Salifort Motors, we have received the results of a recent employee survey. The senior leadership of the HR team gave a task of analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like us to design a model that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points that  is helpful. 


Data Understanding:

For this project, we are working with a data collated by the HR team of Salifort Motors, It contains 15,000 unique entries for employees that have either stopped working, or are still working in the company. The left column which is the outcome variable is a binary entry (0 is employee is still in the company, 1 if the employee has left the company). There are other features such as salary, satisfaction level…

Modeling and Evaluation:

The process began with thorough EDA and data cleaning, and then building a logistic regression model because the outcome is binary, we also built some machine learning algorithms,  including decision tree, random forest, and XGBOOST and tuned the hyper parameters to get the best score possible, we got the champion model to be the tree-based model with an AUC score of 93%, Precision of 87%, Recall of 90%, and F1 score of 96%.


Conclusion:

Based on the model's results, the HR team’s leadership identified key insights and actionable recommendations:
Attrition is linked to poor management practices, evidenced by long working hours, multiple projects, and low satisfaction levels. The team suggests promoting employees with a four-year tenure and reevaluating evaluation criteria to foster a fair and rewarding work environment, reducing turnover and improving employee retention at the company.
