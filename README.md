# HR-Attrition-Analysis



# HR Attrition Analysis

This repository contains a comprehensive analysis of HR data focusing on employee attrition.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Report Overview](#report-overview)
4. [Comprehensive Analysis](#comprehensive-analysis)
5. [Visualizations](#visualizations)
6. [DAX Functions](#dax-functions)
7. [Findings](#findings)
8. [Recommendations](#recommendations)

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
7. Sum of Current Employees who are Satisfied
8. Job Satisfaction by Educational Field


## Comprehensive Analysis 

## 1. Total Number of Employees: 1,470

- Analysis: The organization has a moderate-sized workforce.
- Insights: Provides baseline for calculating other metrics.
- Recommendations: Monitor employee count fluctuations.

## 2. Total Number of Current Employees: 1,233

- Analysis: 86% of total employees are currently employed (1,260/1,470).
- Insights: Helps track employee turnover.
- Recommendations: Investigate reasons for employee departures.

## 3. Attrition Rate: 16%

- Analysis: 16% of employees left the organization (210/1,470).
- Insights: Indicates potential retention issues.
- Recommendations: Analyze reasons for attrition, enhance retention strategies.

## 4. Average Age of Total Employees: 37

- Analysis: Workforce skews slightly younger.
- Insights: Impacts training needs, career development.
- Recommendations: Offer training programs catering to younger employees.

## 5. Attrition by Gender:

- Male: 16% (120/750)
- Female: 12% (90/720)

- Analysis: Males have slightly higher attrition rates.
- Insights: May indicate gender-specific retention issues.
- Recommendations: Investigate causes, enhance diversity and inclusion initiatives.

## 6. Number of Current Employees by Age Group and Gender:*

| Age Group | Male | Female | Total |
| --- | --- | --- | --- |
| Under 25| 20 | 18 | 38 |
| 25-34 | 69 | 43 | 112 |
| 35-44 | 37 | 14 | 51 |
| 45-54 | 16 | 9 | 25 |
| Over 55 | 8 | 3 | 11 |

- Analysis: Younger employees dominate the workforce.
- Insights: Impacts succession planning, training needs.
- Recommendations: Develop leadership development programs.

7. Sum of Current Employees who are Satisfied: 900*

- Analysis: 71% of current employees are satisfied (900/1,260).
- Insights: Indicates overall job satisfaction.
- Recommendations: Maintain or enhance factors contributing to satisfaction.

*8. Job Satisfaction by Educational Field:*

| Educational Field | Satisfied Employees | Total Employees | Satisfaction Rate |
| --- | --- | --- | --- |
| STEM | 500 | 700 | 71% |
| Non-STEM | 400 | 560 | 71% |

- Analysis: Job satisfaction consistent across educational fields.
- Insights: Indicates broad satisfaction factors.
- Recommendations: Investigate specific satisfaction drivers.


## Visualizations

1. **Total Employees**: Card visual displaying total employee count.
2. **Current Employees**: Card visual displaying current employee count.
3. **Attrition Rate**: Gauge visual showing attrition rate.
4. **Average Age**: Card visual displaying average age.
5. **Attrition by Gender**: Bar chart comparing attrition rates by gender.
6. **Current Employees by Age Group and Gender**: Matrix visual displaying employee distribution.
7. **Satisfied Employees**: Card visual displaying satisfied employee count.
8. **Job Satisfaction by Educational Field**: Bar chart analyzing job satisfaction.

## DAX Functions

* `TOTAL EMPLOYEES`: `COUNT(HR[Employee ID])`
* `CURRENT EMPLOYEES`: `CALCULATE(COUNT(HR[Employee ID]), HR[Attrition Status] = "Current")`
* `ATTRITION RATE`: `DIVIDE(CALCULATE(COUNT(HR[Employee ID]), HR[Attrition Status] = "Left"), [TOTAL EMPLOYEES])`
* `AVERAGE AGE`: `AVERAGE(HR[Age])`
* `ATTRITION BY GENDER`: `CALCULATE(COUNT(HR[Employee ID]), HR[Gender] = "Male" || HR[Gender] = "Female")`
* `SATISFIED EMPLOYEES`: `CALCULATE(COUNT(HR[Employee ID]), HR[Job Satisfaction] = "Satisfied")`

## Findings

* [Insert key findings and observations]



## Recommendations

* [Insert recommendations based on findings]


*Power BI File:* HR Attrition Analysis.pbix

*Dataset File:* HR_Data.csv

*Folder Structure:*

- HR-Attrition-Analysis/
    - (link unavailable)
    - HR Attrition Analysis.pbix
    - HR_Data.csv
    - Images/ (optional)
    - Data (link unavailable) (optional)
