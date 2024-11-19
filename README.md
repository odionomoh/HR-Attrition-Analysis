## HR-Attrition-Analysis

# Analysis Title: HR Data-Driven Insights

This repository contains a comprehensive analysis of HR data focusing on employee attrition.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Report Overview](#report-overview)
4. [Comprehensive Analysis](#comprehensive-analysis)
5. [Visualizations](#visualizations)
6. [DAX Functions](#dax-functions)

---
## Introduction

This analysis aims to provide insights into employee attrition, demographics, and job satisfaction.

## Dataset

* HR data ( Excel file: HR Data.xlsx)
* Key Columns:
 	 + Attrition
 	 + CF_age band
	 + CF_attrition label
	 + Department
	 + Education Field
	 + Gender
 	 + Job Role
 	 + CF_current Employee
 	 + Employee Count
	 + Job Satisfaction

 
## Report Overview

The report covers the following metrics:

1. Total Number of Employees
2. Total Number of Current Employees
3. Attrition Rate
4. Average Age of Total Employees
5. Attrition by Gender
6. Number of Current Employees by Age Group and Gender
7. Job Satisfaction by Educational Field


## Comprehensive Analysis 

## Section 1: Workforce Overview

1. Total Number of Employees

- Metric: 1,470
- Analysis: Moderate-sized workforce, impacting HR operations, training, communication, and employee engagement.
- Insights: Baseline for calculating HR metrics (turnover rate, training participation, employee satisfaction).
- Recommendations:

    1. Monitor employee count fluctuations.
    2. Analyze workforce size impact on HR operations.
    3. Optimize resource allocation.
    4. Foster positive work environment.
    5. Regularly review HR policies.


## Section 2: Employee Retention

2. Total Number of Current Employees

- Metric: 1,233 (84% retention)
- Analysis: Moderate employee turnover; potential room for improvement.
- Insights: Tracks employee turnover; informs retention strategies.
- Recommendations:

    1. Investigate employee departure reasons.
    2. Enhance retention strategies.
    3. Develop retraining programs.
    4. Monitor employee satisfaction.

3. Attrition Rate

- Metric: 16%
- Analysis: Moderate attrition; potential retention issues.
- Insights: Highlights areas for improvement in employee retention.
- Recommendations:

    1. Analyze attrition reasons.
    2. Develop targeted retention strategies.
    3. Enhance employee engagement.
    4. Monitor workplace issues.


## Section 3: Demographics

4. Average Age of Total Employees

- Metric: 37
- Analysis: Workforce skews younger, impacting training, career development, succession planning.
- Insights: Informs HR strategies for employee development.
- Recommendations:

    1. Offer training programs for younger employees.
    2. Develop leadership development programs.
    3. Foster mentorship opportunities.
    4. Plan for succession.


5. Attrition by Gender

- Metric: Males (63.29%); Females (36.71%)
- Analysis: Potential gender-specific retention issues.
- Insights: Highlights diversity and inclusion concerns.
- Recommendations:

    1. Investigate gender disparity causes.
    2. Enhance diversity and inclusion initiatives.
    3. Develop targeted retention strategies.
    4. Monitor workplace issues.


## Employee Demographics by Age Group and Gender

6. Metric: Number of Current Employees by Age Group and Gender

## Data:

| Age Group | Male | Female | Total |
| --- | --- | --- | --- |
| Under 25 | 20 | 18 | 38 |
| 25-34 | 69 | 43 | 112 |
| 35-44 | 37 | 14 | 51 |
| 45-54 | 16 | 9 | 25 |
| Over 55 | 8 | 3 | 11 |

Analysis:

The workforce is predominantly composed of younger employees, with:

- 38 employees under 25 (31% of total)
- 112 employees between 25-34 (57% of total)

This age distribution indicates:

- Potential succession planning challenges
- Increased training needs for younger employees
- Opportunities for leadership development programs

Insights:

This demographic breakdown highlights:

- The importance of investing in employee development programs
- The need for effective succession planning strategies
- Potential areas for improvement in employee retention

Recommendations:

1. Develop leadership development programs for younger employees.
2. Create targeted training initiatives for employees under 25.
3. Implement succession planning strategies to address potential gaps.
4. Monitor employee retention rates across age groups.
5. Analyze the impact of age demographics on workforce diversity.


## Job Satisfaction by Educational Field

Table:

| Job Role | Very Dissatisfied | Dissatisfied | Satisfied | Very Satisfied | Total |
| --- | --- | --- | --- | --- | --- |
| Healthcare Representative | 2 | 2 | 1 | 4 | 9 |
| Human Resources | 5 | 2 | 3 | 2 | 12 |
| Laboratory Technician | 20 | 8 | 21 | 13 | 62 |
| Manager | 1 | 2 | 1 | 1 | 5 |
| Manufacturing Director | 2 | 2 | 4 | 2 | 10 |
| Research Director | 0 | 1 | 1 | 0 | 2 |
| Research Scientist | 13 | 10 | 15 | 9 | 47 |
| Sales Executive | 16 | 9 | 18 | 14 | 57 |
| Sales Representative | 7 | 10 | 9 | 7 | 33 |
| Total | 66 | 46 | 73 | 52 | 237 |

Analysis:

1. Overall Job Satisfaction: 73 employees are satisfied, while 46 are dissatisfied.
2. Highest Job Satisfaction: Laboratory Technician (21 satisfied, 13 very satisfied)
3. Lowest Job Satisfaction: Human Resources (5 very dissatisfied, 2 dissatisfied)
4. Job Roles with High Dissatisfaction: Research Scientist (13 very dissatisfied), Sales Executive (16 very dissatisfied)

Insights:

1. Job satisfaction varies significantly across job roles.
2. Laboratory Technicians are generally satisfied, while Human Resources employees are dissatisfied.
3. Research Scientists and Sales Executives experience high levels of dissatisfaction.

Recommendations:

1. Investigate reasons for dissatisfaction in Human Resources and Research Scientist roles.
2. Implement targeted training initiatives for Laboratory Technicians to maintain satisfaction.
3. Address workplace issues contributing to dissatisfaction in Sales Executive roles.
4. Monitor job satisfaction across all roles to identify areas for improvement


## Visualizations

![HR image](https://github.com/user-attachments/assets/47f6e99c-c5e3-4f01-b47c-9b8e80714344)




## DAX Functions

* `Average Age`= ` AVERAGE('Table'[Age])`
* `Attrition Rate`= ` SUM('Table'[Attrition Count]) /SUM('Table'[Employee Count])`


Power BI File: HR Attrition Analysis.pbix


    
