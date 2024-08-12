# HR Analysis

I used two datasets to create HR Analytics Power BI Dashboard and the HR Employee data joined using left join. On the dashboard, there are three pages: Home, Employee, and Department.

- Home page
    - Active workers: if the employee works less than 18 years
    - Due to retreanchment: if the employee works equal or more than 18 years
    - Distance from home: Far (>=20), Close (>=10), else is Very Close
    - Performance level: High (if performance rating = 3), else is Low
    - Need training: if the training times last year of the employee is less than 3, else no need training
    - Due to promotion: if the last promotion of the employee is equal or more than 10 years, else no due to promotion
- Employee page
    - List of employee that due to retreanchment
    - List of employee that due to promotion
    - Total employee by Percent salary hike
- Department page
    - Total employee that due to retreanchment and promotion by Department
    - Total employee that due to retreanchment and promotion by Job Role
    - Total employee by Job Role and Job Satisfaction
    - Monthly rate by Job Role
