# Pewlett Hackard Analysis

## Overview of the Analysis

Pewlett Hackard is large, successful company boasting thousands of employees. The company wants to do an employee research analysis to prepare for the future. This will involve giving its older employees a generous retirement package to phase them out. Because this will leave thousands of job openings for the company, we need build an employee database, using SQL, to identify who will be offered retirement, which positions need to be filled, and who should mentor and train these future Pewlett Hackard employees.

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

* Using the same chart above, we see that Pewlett Hackard will need to replace **nearly 51,000 (or 64%) senior and manager employees** who will retire soon

* There are **1,549** employees at the company who are eligible to mentor (born in 1965) the future staff as older employees retire

![mentorship_eligibility](https://github.com/dwwatson1/Pewlett-Hackard-Analysis/blob/main/Images/mentorship_eligibility.PNG)

* Referencing the same chart above, **about 700 (or 46%) of the eligible mentors are senior employees** and will be tasked with training the future of the company

## Summary of the Analysis

### Important Things to Note
  
