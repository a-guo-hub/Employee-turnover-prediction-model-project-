# Employee-Turnover-Prediction-with-Random-Forest-

## Overview
The goal of this project is to build a machine learning model that predicts whether an employee will leave the company
based on their job title, department, number of projects, average monthly hours, and any other relevant data points. This 
project utilized Salifort Motors employee data. The final random forest model performed with 96% accuracy 
and 87% precision. Based on the model, the last evaluation score, number of projects, tenure  and being overworked were the most influential
in determining the departure of an employee.

## Business Undertanding
A well-designed model will enable the company to enhance employee retention and job satisfaction, while also reducing the costs and time associated
with training new hires. By identifying the factors that influence employee departures, Salifort Motors can take proactive and corrective measures to 
address these issues.

## Data Understanding
The data for this project came from Kaggle which comprised of 11 991 rows representing individual employees, and 10 columns, of which 9 are features. 
These features included details such as satisfaction level, the number of projects an employee contributes to, the average number of hours worked per month, 
and additional relevant information. Out of the 11 991 employees, approximately 83.4% stayed and 16.6% left. 

A feature was engineered to indicate whether an employee was overworked (working more than 175 hours per month). The columns for satisfaction levels and 
average monthly hours were dropped, as they could be unrepresentative under certain circumstances, potentially negatively impacting the model's accuracy.

## Modeling and Evaluation
A random forest model comprising 300 decision trees was used to determine feature importance in who would stay and leave the company. The top 3 most important
factors were the score of the last evaluation, the number of projects and tenure. The overall model performed with 96% accuracy and 87% precision.

## Conclusion
To retain employees, it is recommended to implement a cap on the number of projects to prevent burnout, consider promoting employees with four or more years of tenure, 
and either reward longer working hours or avoid requiring them. Clear communication of overtime pay policies and workload expectations, along with fostering discussions 
on work culture, can improve job satisfaction. Additionally, evaluation scores should be based on contribution and effort, not just hours worked.
