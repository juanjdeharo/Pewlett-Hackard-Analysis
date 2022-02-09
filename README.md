# Pewlett_Hackard_Analysis

## Overview of the analysis:

> Manager has asked Bobby and I to gather more information on the number of retiring employees per title and the employees that are eligible to participate in the mentorship program.

1. What is the number of retiring employees by title?
2. What employees are eligible for the mentorship program?
3. Write a report analyzing the findings

## Resources:
> Data Source: employees.csv, departments.csv, dept_emp.csv, dept_manager.csv, mentorship_eligibility.csv, retirement_info.csv,
retirement_title.csv, retiring_titles.csv, salaries.csv, titles.csv, unique_titles.csv
> Software: pgAdmin 4, postgreSQL, Visual Studio

## Results:


### Number of retiring employees by title:
![PyBer Summary DataFrame](https://github.com/juanjdeharo/Pewlett-Hackard-Analysis/blob/main/Retiring%20Employees%20by%20Title.PNG)
> The results indicate that we want to start thinking about making the most replacements in the Senior Engineer and Senior Staff in general. 
> This makes sense however as they have "Senior" in the title which indicates some experience. 
> The next title with the most to-retire employees is the Engineers.

### Employees eligible for mentorships: 
> This can be viewed in the exported mentorship_eligibility file. 
> There are a total of 1549 employees eligible for mentorships.

## Symmary: 
> It would seem that the amount of Engineers eligible for mentorships and the amount of Staff employees eligible for memberships are far lower than the amount of "Senior" employees that could retire in the near future. This means that a lot of outside resources would be needed unless Pewlett Hackard puts more programs in place to ready its current employees for mentorships.
> Other queries that might be helpful to this company would be to see what the reatio of men to women is depending on the title, and if there is a major disparity (for example way more men than women as Senior Engineers) this needs to be addressed.
> Another helpful table would be to use hire_date from Employees to see who are the oldest hired employees that still do not qualify for mentorships, and consider terminating employees that do not grow.
