# HR-Attrition-Data-Analysis-Python

## Business Problem
The HR department wants to understand which factors are associated with attrition.

## Dataset
HR Analytics Employee Attrition dataset — 1,480 employee records across 38 columns, including demographics, job role, compensation, satisfaction scores, and tenure.

Dataset sourse: https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset/data

## Objectives
* Explore and clean data
* Analyse attrition
* Identify patterns
* Produce business recommendations

## Scope
This analysis focuses on a selected set of relationships, such as department, overtime, job satisfaction, and tenure, rather than every variable in the dataset. Other factors, such as income, distance from home, work-life balance, or job role, could be explored in further analysis.

## Tools & Skills Demonstrated
* Python (Pandas, NumPy, Matplotlib)
* Reading CSV files
* Data cleaning (duplicates, missing values)
* GroupBy operations
* Missing value analysis
* Data visualisation


## Key Findings
* Overall attrition rate: 16.08%
* Employees working overtime had a much higher attrition rate (30.62%) than those who didn't (10.36%) which is the strongest pattern in the data.
* Sales had the highest departmental attrition rate (20.67%), ahead of HR (19.05%) and R&D (13.75%).
* Employees with 0–2 years of tenure left at nearly double the rate (29.82%) of any other tenure group.
* Attrition generally declined as job satisfaction increased, though the relationship wasn't fully linear.

## Business Recommendations
* Review workload in high-turnover departments, particularly Sales.
* Improve retention during the first two years, when attrition risk is highest.
* Monitor overtime as a potential early-warning indicator for attrition risk.

## Project Structure
* `HR_Analytics_Project.ipynb` — full analysis notebook (EDA, cleaning, visualisation, insights)
