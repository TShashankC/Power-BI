# HR Analytics Dashboard using Power-BI

# Objective
To help organizations to improve employee performance and retention rates( Attrition ) through HR Analytics Dashboard 


# About Data
There are 1470 employee records with 39 columns, ranging from employee ID, Age, Daily Rate, Department, Attrition etc are a few columns. 


# Data Cleaning and Processing
The csv file has been imported into Power BI, the data is transformed using Power Query Editor. Initially the data type of each column is detected by default. Group by on Emp ID is done to find ant duplicate employee records and found a few, which were deleted as pert of the process. Another column Business travel has 4 catergories, out of which 2 catergories meant to be same but named differently. Therefore, renamed so there are 3 categories in total. Attrition column contains "Yes" or "No", to use it as a KPI, "Yes" were changed to 1 and "No" to 0.
A new measure names Attrition Rate is created to display it in percent.

# Report Buidling

Cards are used to produce the KPI's like Attrition, Number of Employees, Attrition, Attrition Rate, Average Salary and years at company. A donut chart is used to show the atttributuon rate by education. Attrition Rate by Age is displayed using bar chart. Similarly, Attrition Rate by job role, salary slab, years at company are shown in the dashboard. 

# Insights and Conclusion
- Men attrition rate stood at 17%, which is higher than the average. Men aged 26-35 and salary up to 5K are exiting the organisation.
- The same trend has been seen in the women employees as well.
- Women Sales excetives are exiting the organisation at higher rates.
- Employees in the salary slab of upto 5K are earning less than the organisation's average of 6.5K.
   

