# Human Resources Dashboard

## Project Overview
The dataset was obtained from the Kaggle [Human Resources Dataset](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set).


The purpose of the project was to gain valuable insights to improve diversity and inclusivity.  

## Objectives
- Determine the Headcount of active Employees.
- Investigate Company Demographics.
- Examine the Trend of Active Employees over Time.
- Review Employee Satisfaction and Engagement Ratings.
- Examine Absenteeism and Tardiness.
- Examine Department Gender Distribution.
- Determine the Top Reasons for Employee Churn.

## Results
### Executive Summary
![HR Dashboard Executive Summary 2](https://github.com/frantzalexander/Dashboard-HR/assets/128331579/7322d384-03c3-4b3b-8f74-9ec07f101377)



### Department Analysis
![HR Dashboard Departments](https://github.com/frantzalexander/Dashboard-HR/assets/128331579/29e2aaf4-eec3-448f-a6a7-1fe3f8679c7c)




### Key Recommendations
There is high absenteeism among women in the production department. 

The Top 3 reasons for employee churn are: Unhappiness, Leaving for another position & seeking greater compensation. 

The average satisfaction was measured at 3.89 out of 5 with Average employee engagement of 4.12. 

Communicating the issue of absenteeism to employees and creating policies that boost morale and engagement would go a long way towards addressing these issues. 




## Process

```mermaid
flowchart TD
start(((START)))
import[Import Dataset into Python]
clean[Clean Dataset]
split[Data Normalization: Create Data Tables & Fact Tables]
quality[Improve Data Quality & Integrity]
bi[Power BI: Import Data Tables & Fact Tables]
whiteboard[Whiteboard: Determine Visualization KPIs]
exec[Executive Summary]
active[Headcount of Active Employees]
total_male[Total Number of Male Employees Hired]
total_female[Total Number of Female Employees Hired]

departments[Department Summary]

finish(((END)))

start --> import
import --> clean
clean --> split
split --> quality
quality --> bi
bi --> finish
