# Pewlett Hackard Analysis

## Overview of the Analysis

Pewlett Hackard is large, successful company boasting thousands of employees. The company wants to do an employee research analysis to prepare for the future. This will involve giving its older employees a generous retirement package to phase them out. Because this will leave thousands of job openings for the company, we need build an employee database, using SQL, to identify who will be offered retirement, which positions need to be filled, and who should mentor and train these future Pewlett Hackard employees.

Before I began this analysis I built a entity relationship diagram (ERD) to map out the six original csvs provided and analyze their relationships to one another. What I noticed is that many of the csvs shared similar column names, which will make it easier to query and create cleaner data using SQL.

![EmployeeDB](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png)

### Analysis Resources
Data Sources| 
------------- | 
[count_by_dept](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/count_by_dept.csv)  | 
[departments](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/departments.csv) | 
[dept_emp](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/dept_emp.csv) |
[dept_manager](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/dept_manager.csv) |
[emp_info](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/emp_info.csv) |
[employees](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/employees.csv) |
[manager_info](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/manager_info.csv) |
[mentorship_eligibilty](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibilty.csv) |
[retirement_info](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/retirement_info.csv) |
[retirement_titles](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv) |
[retiring_titles](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) |
[salaries](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/salaries.csv) |
[titles](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/titles.csv) |
[unique_titles](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv) |
 
* Software: Pg Admin - PostgreSQL 11 
* Queries: [Queries](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Queries/queries.sql) & [Employee_Database_challenge](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_challenge.sql)

## Results of the Analysis

### Overview of Results 
* There are **90,398** employees at Pewlett Hackard who are eligible for retirement (born between 1952 and 1955)

![retiring_titles](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Images/retiring_titles.PNG)

* Using the same chart above, we see that Pewlett Hackard will need to replace **nearly 58,000, or 64% of all eligible retiring employees, are senior and manager employees**

* There are **1,549** employees at the company who are eligible to mentor (born in 1965) the future staff as older employees retire

![mentorship_eligibility](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Images/mentorship_eligibility.PNG)

* Referencing the same chart above, **about 700 (or 46%) of the eligible mentors are senior employees** and will be tasked with training the future of the company

## Summary of the Analysis

### Important Things to Note
  
Pewlett Hackard will need to preparing for the future quickly. Upon further analysis of the entire employee count, there are 240,124 employees. See count by title below.

![employee_count](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Images/employee_count.PNG)

This means that **38%** of the entire company will be retiring soon, which is truly a __silver tsunami__. If we break down by title which have the highest percentage retiring, **Staff** and **Engineer** have the highest with **48%** and **46%** respectively.

In addition to filling a large percentage of mid-level roles, the company is left to fill nearly 58,000 senior level roles with only 700 mentors. That is a very tall task because each mentor will have 80 employees to train, assuming they only want to promote from within.

If shift our attention to the next wave of employees who will be retiring (born between 1956 and 1959) the picture is just as scary. Nearly 74,000 employees will be a part of the continued silver tsunami. It's important to note that **5 Managers** willl be a part of this wave. And in the previous wave, 2 Managers will have retired. In the current listing of eligible mentors, there are no Managers. That is particularly alarming when 7 of 9 will retire in the next 5-10 years. I recommend part of this second wave of retiring employees be added to the list of mentors, especially the Managers who can likely train employees for all types of roles.

![retirement_ready_mentors](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Images/retirement_ready_mentors.PNG)
