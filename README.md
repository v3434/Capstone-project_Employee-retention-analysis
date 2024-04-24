# Employee Retention Analysis Using Machine Learning 

The primary goal of this project is to improve employee retention rates at Salifort Motors by utilizing data-driven insights to identify factors contributing to turnover. By analyzing collected employee data and constructing a predictive model, the project aims to forecast potential departures and uncover underlying reasons for attrition. The ultimate objective is to implement strategies and solutions that address these factors, thereby increasing overall employee satisfaction and retention.

## Project Overview:

Main Goal of The Project:

* Understand factors influencing employee attrition.
* Build a predictive model for employee retention.
* Provide actionable recommendations to enhance retention.
First Exploratory data analytics was performed on the dataset to understand the variables and clean the dataset , followed by Data visualization where important insights were found and was used for selecting ML model.
for predictive analysis. Since target feature belongs to categorical datatype, Logistic regression and Tree-based models were chosen for modelling.

## Business Understanding :

This seeks to understand and mitigate employee turnover through data analysis. By identifying key factors driving departures and implementing targeted retention strategies, the company aims to reduce costs, maintain operational stability, enhance employee satisfaction, and strengthen its employer brand for sustained success in the competitive market.

## Data Understanding :

The top significant features that contributes to employee leaving are 'last_evaluation' , 'number_project' , 'tenure' and 'overworked' . this was observed from the feature importance graph generated using the ML models .
![image](https://github.com/v3434/Capstone-project_Employee-retention-analysis/assets/70278692/144f4c37-8f1e-4525-a1a6-476925326edf)
![image](https://github.com/v3434/Capstone-project_Employee-retention-analysis/assets/70278692/56100035-b2dd-4606-a901-27c8325dadc4)

## Modeling and Evaluation :

ML Model : Desicion Tree , Random Forest , Logistic Regression
Evaluation Metrics : AUC , precision , accuracy , f1-score and recall .

## Conclusion:
For detailed insights explanation and results , refer the jupyter notebook which includes key insights , explanations , data visualization graphs and results summary .
It was evident that employees at company overworked . To enhance employee retention, 

stakeholders could consider the following recommendations:
* Limit the number of projects per employee.
* Promote employees with four or more years of tenure or investigate their dissatisfaction.
* Offer incentives for longer hours or eliminate mandatory overtime.
* Ensure clarity on overtime pay policies and workload expectations.
*Conduct discussions to improve company culture.
*Implement fair evaluation criteria irrespective of monthly work hours.




