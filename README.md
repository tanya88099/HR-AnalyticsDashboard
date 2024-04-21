# HR-AnalyticsDashboard

#Measures:
Count of Employee: Count(EmpID)
Average Age: Avg(Age)
AttritionCount: transform the column attrition in the case(i.e if attrition == "yes" then 1 else 0, and use this formula: SUM(AttritionCount)
AttritionRate measure: =SUM([AttritionCount])/SUM([EmployeeCount])
Average Salary: Avg(MonthlyIncome)
Average: Avg(YearsAtCompany)

#StoryTelling:
Attrition By Education
Piechart shows each EducationField Attrition Count.

Attrition By Age
this shows which age group maximum leaving the company.

Attrition By Salary 
Salary Slab by attritioncount.

Top 5 Attrition By Job Role
 Job Role by attrition Count

 Employees leave company at year
this graph shows attrition count by duration(year) of the employee in a company.

