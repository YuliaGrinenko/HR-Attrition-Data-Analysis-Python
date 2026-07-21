# HR-Attrition-Data-Analysis-Python

## Business Problem

Employee attrition can lead to increased recruitment costs and reduced productivity. The HR department wants to identify the factors associated with employee turnover in order to better understand attrition patterns and support employee retention strategies.

## Objectives
- Explore and clean the HR dataset.
- Calculate the overall employee attrition rate.
- Analyse attrition across selected employee characteristics, including department, overtime, job satisfaction, and tenure.
- Identify patterns associated with employee turnover.
- Provide data-driven business recommendations.
- 
## Dataset
HR Analytics Employee Attrition dataset containing **1,470 employee records** and **38 variables**, including employee demographics, job role, compensation, satisfaction scores, performance, and tenure.

**Source:** Kaggle – HR Analytics Employee Attrition Dataset

## Scope
This analysis focuses on a selected set of relationships, such as department, overtime, job satisfaction, and tenure, rather than every variable in the dataset. Other factors, such as income, distance from home, work-life balance, or job role, could be explored in further analysis.

## Tools & Skills Demonstrated
* Python (Pandas, NumPy, Matplotlib)
* Data cleaning (duplicates, missing values)
* GroupBy operations
* Missing value analysis
* Data visualisation


## Key Findings
* Overall attrition rate: 16.1%
* Employees working overtime had a much higher attrition rate (30.62%) than those who didn't (10.36%) which is the strongest pattern in the data.
* Sales had the highest departmental attrition rate (20.67%), ahead of HR (19.05%) and R&D (13.75%).
* Employees with 0–2 years of tenure left at nearly double the rate (29.82%) of any other tenure group.
* Attrition generally declined as job satisfaction increased, though the relationship wasn't fully linear.

## Business Recommendations

- Review workload and overtime practices to reduce employee turnover.
- Prioritise retention initiatives during employees' first two years with the company.
- Develop targeted retention strategies for departments experiencing higher attrition, particularly Sales

## Project Structure
* `HR_Analytics_Project.ipynb` — full analysis notebook (EDA, cleaning, visualisation, insights)
