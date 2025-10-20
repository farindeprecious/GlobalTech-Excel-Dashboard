# GlobalTech-Excel-Dashboard: An Excel-based data analysis project showcasing workforce insights, salary comparisons, and retention analysis for GlobalTech Solutions.
________________________________________
## Table of Content
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Sourcing](#data-sourcing)
- [Data Transformation](#data-transformation)
- [Analyzing and Visualization](#analyzing-and-visualization)
- [Conclusion and Recommendation](#conclusion-and-recommendation)
  
### Introduction
This project was completed as part of the Techsavia Excel Project. The goal was to analyze the employee data of GlobalTech Solutions and develop an interactive Workforce & Compensation Dashboard using Microsoft Excel.
The dashboard provides a one-page overview of the company’s workforce structure, salary distribution, years of experience, and retention risk.
This project helped me, as a beginner in data analytics, to apply foundational Excel skills such as Analysis, pivot tables, and visualization to uncover valuable business insights.
________________________________________
### Problem Statement
The management of GlobalTech Solutions wanted to understand:
- Which employees have been with the company for more than 10 years.
- Departments with the highest and lowest experience levels.
- Salary distribution across departments and countries.
- Employees earning above their department’s average salary.
- Workforce distribution by city and country.
- Retention risks — identifying employees with less than 3 years of experience.
- Whether there’s a relationship between salary and years of experience.
To solve these, an Excel-based dashboard was designed to summarize key findings and display workforce and compensation patterns clearly.
________________________________________
### Data Sourcing
The dataset used for this analysis was provided as part of the Techsavia training dataset.
It contains 30 employee records across 9 columns, including:
- Employee ID
- Full Name
- City
- Country
- Job Title
- Department
- Hire Date
- Salary
- Years of Experience
The data represents a simplified view of a company’s workforce used for analytical practice and visualization.
________________________________________

### Data Transformation
Before analysis, the dataset underwent transformation in Microsoft Excel using features such as:
- Extracting the hire year from the hire date using =YEAR(cell)
- Creating calculated columns for analysis, including:
- Employee class (“High Class”) — employees earning above their department’s average
Data was then summarized using Pivot Tables and Calculated Fields to generate the required metrics.
________________________________________
### Analyzing and Visualization
Key Performance Indicators (KPIs)
- Total Employees: 30
- Number of Departments: 6
- Most Common Job Title: Developer
<img width="1274" height="536" alt="My Dashboard" src="https://github.com/user-attachments/assets/21391ce9-d430-4105-a1c2-e834888c24f2" />

Link to my Excel dashboard : https://1drv.ms/x/c/719b373f3765f6d2/ES3d62C7V_VJvHFxLzX19kwBvJr5tlYvdeA0g9iuJH0Qcw?e=Mk2rGg
________________________________________


#### Visual Insights
Top 3 Departments by Experience (Stacked Bar Chart)
- Sales, Marketing, and IT had the highest total years of experience, showing strong departmental expertise.

Total Salary by Department (Stacked Column Chart)
- IT had the highest total salary, while Operations had the least — indicating larger headcount or higher pay scales in IT.

Average Salary by Department (Stacked Column Chart)
- Operations had the highest average salary, while Marketing had the lowest.

Top 5 Earners (Stacked Column Chart)
- Highlighted key employees earning the most across the company.

Employee Distribution by Department (Bar Chart)
- IT: 9 employees
- Finance: 5
- Sales: 5
- Marketing: 5
- HR: 4
- Operations: 2
- IT department leads the workforce.

Bottom 3 Departments with Longest-Serving Employees (Stacked Column Chart)
- IT, Marketing, and Sales have the longest-serving employees.

Employee Distribution by Country (Stacked Column Chart)
- The U.S. has the highest number of employees, while Germany has the least.

Salary vs. Years of Experience (Line Chart)
- The relationship was zig-zag, showing no consistent increase in salary with experience — suggesting salary differences are influenced by roles or departments rather than tenure alone.

Cities with the Highest Number of Employees (Stacked Bar Chart)
- Berlin, Paris, and Toronto have equal numbers of employees.
#### Slicers Used
- Class: (High Class vs Others)
- Job Title: for interactive role-based insights
________________________________________
### Conclusion and Recommendation
#### Conclusion
This project demonstrates how Microsoft Excel can be used for end-to-end workforce analysis — from transforming data to building interactive dashboards for management decision-making.
#### Recommendations
- Review salary structures in departments like Marketing to ensure internal equity.
- Retain experienced employees in IT, Sales, and Marketing through mentorship and growth programs.
- Investigate pay inconsistencies to ensure fair compensation across roles.
- Strengthen workforce diversity by expanding hiring across underrepresented countries.
- Introduce career development programs to support newer employees (less than 3 years of experience) and reduce turnover.

