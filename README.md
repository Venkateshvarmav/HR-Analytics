# HR-Analytics

# Coffee Shop Sales

Dashboard Link - [https://app.powerbi.com/groups/me/reports/2fb98590-42f4-4b51-be44-6c55404ed16f/b6e7faa788c2079b6b27?experience=power-bi&clientSideAuth=0](https://app.powerbi.com/groups/me/reports/a44adf82-96bc-4082-8d77-2eb67d3ae275/4e55e4468da4ca3e3991?experience=power-bi)

## Problem Statement

•	This dashboard allows the HR or the leadership to understand the reason for attrition and can try to improve themselves to reduce the attrition rate and provide more opportunity for the employees


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset" to check the empty and error percentage.
- Step 4 : It was observed that in none of the columns errors & empty values were present
- Step 5 : Since the data contains various parameters such as Salary, Age, Job Title and Job Satisfacation Bar Graphs and metrics table have been used to represent the findings.
- Step 6 : Visual filters (Slicers) were added for Job Role and Gender
- Step 7 : Metrics table has been used as a heat map to show the most and least attrition by job role against the job satisfaction
- Step 8 : Pie chart has been used to show the attrition by the employee education
- Step 9 : Area chart has been used to show the attrition by years of employement in the company
- Step 10 : Cards have been used to show the KPI such as Total Number of Employees, Count of Attrition, Attrition rate, Avg Age of the employees, Avg Salary, Avg years of the employee spent in the organization
  
- Step 12 : New measure was created to find the attrition

```DAX
Attrition_Rate = SUM(HR_Analytics[Attrition_count])/SUM(HR_Analytics[EmployeeCount])
```
        
# Snapshot of Dashboard (Power BI Service)

![image](https://github.com/user-attachments/assets/9bfded20-b44b-4bf5-9b42-b19832532535)


 
 # Report Snapshot (Power BI DESKTOP)

![image](https://github.com/user-attachments/assets/be94bcf3-c163-45f7-80fc-47b2310a7ba0)



# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Highest and Lowest Attrition by Education

  Highest Attrition by education - Life Sciences - 37.6%
  
  Lowest Attrition by education - Human Resources - 3%
 

### [2] Highest and Lowest Attrition by Age

    Highest Attrition by Age - 36-35 - 116 employess
  
    Lowest Attrition by Age - 55+ - 8 employees 

### [3]  Highest and Lowest Attrition by Job Satisfaction and Job Jole


    Highest Attrition by Job Role - Laboratory Technicians - 62 employees
  
    Lowest Attrition by Job Role - Research Directors - 2 employees

           
###  [4] Attrition by gender

Male - 150
Female - 87
  
  
### [5] Attrition By Salary
  
163 employees have left the company drawing salary less than 5000
5 employees have left the company drawing salary more than 15000

### [5] Attrition By Years in the company
  
51 employees with 1 year have left the company 
Only 2 people with over 10 years with the company have quit

 With this data the HR BP can work with the heads of the Laboratory Technicans, Sales Executive, Research Scientist, Sales Representative to find the main concern with majority of the employees leaving the company belong to their team and take corrective measures



 ## Analysis

1. With the above dashboard we can determine the best and worst role with the job satisfaction.
 
2. We can also determine that the salary seems to be the main concern for the attrition within employees drawing lower salary
   
3. Based on the data from the attrition by eductation the leadership need to focus on making sure the employees are working based on their educational background

## Author - Venkatesh Varma V

This project is part of my portfolio, showcasing my Power BI skills essential for Data Analyst roles.
