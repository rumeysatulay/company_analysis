# Company Analysis

## Overview 

In this project, I examine company insights using an imaginary dataset. The dataset includes employee information such as department, salary contracts, and gender. With this information, we can gain valuable insights into the company.

## Dataset

The dataset used in this project is sourced from a Udemy course: [The Business Intelligence Analyst Course](https://www.udemy.com/course/the-business-intelligence-analyst-course-2018/?couponCode=KEEPLEARNING). It consists of five tables:
1. **departments**: `dept_no`, `dept_name`
2. **dept_emp**: `emp_no`, `dept_no`, `from_date`, `to_date`
3. **dept_manager**: `emp_no`, `dept_no`, `from_date`, `to_date`
4. **employees**: `emp_no`, `birth_date`, `first_name`, `last_name`, `gender`, `hire_date`
5. **salaries**: `emp_no`, `salary`, `from_date`, `to_date`"

## Project Goals

In this project, I examine the gender analysis of employees. First, I compare the number of female versus male employees over the years. Then, I analyze salary data, comparing salaries by year and gender. Additionally, I conduct a salary analysis across different departments and evaluate the percentage of male and female employees whose salaries are above the average salary. I also analyze employees who have changed departments and identify the departments with the highest turnover.

## Process

SQL was the cornerstone of my analysis, enabling me to thoroughly examine the data and uncover crucial insights. I used Power BI for visualizing the data.

## Outcomes

- Firstly, I examine the number of employees by year to compare genders. Despite the total number of employees over the years, female employees consistently make up 40% of the employees.

![1](https://github.com/user-attachments/assets/3865d10c-9700-49c0-b7ee-f199b8a70cee)

- Secondly, we analyzed the average salaries of male and female employees throughout the year. As shown in the graph, the salary trend has followed a similar pattern for both genders. The salary increases over the years have also been at an equal rate.

![2](https://github.com/user-attachments/assets/6944dbce-1629-4e77-b96b-c85b3aaacb33)

- When we check the average salary of all employees, it is $63,761.20. We then examine how many female employees have a salary above this average. It turns out that 44.18% of female employees have salaries above the average, compared to 44.05% of male employees. Therefore, we can conclude that there is no significant gender inequality in terms of salary.

![6](https://github.com/user-attachments/assets/4f0e1a5a-2e50-46a9-a052-c6c5dff2210f)

- Another analysis focused on the changes in average salaries of employees across different departments over the years. As you can see, the average salary increase for employees in all departments has been very similar. This could be attributed to both the company’s growth and nationwide inflation. The department with the highest average salary is Sales, followed by Marketing and Finance. On the other hand, the department with the lowest average salary is Human Resources, with Quality Service also being one of the lower-paid departments. Development, Production, and Research departments have average salaries below the overall average, with similar levels among them

![3](https://github.com/user-attachments/assets/85dfed34-5989-4200-9bf6-4d4978ffb307)

- In the `dept_emp` table, we can see the departments where employees worked and the duration of their employment. We observe that some employees changed departments within the company, working in two different departments. A total of 31,579 employees changed departments over a 17-year period. Based on this data, we created a scoring system for each department. A department receives +1 point for each employee who joins it and -1 point for each employee who leaves it. This comparison, however, is based solely on employees changing departments within the company.

![8](https://github.com/user-attachments/assets/92d17b57-21e4-482c-89e2-6fff34fe2b82)

- When we look at the department comparison chart, Customer Service is the most preferred department, having the highest score, which indicates that many employees transfer to the Customer Service department. It is followed by the Research, Marketing, Quality Management, and Production departments. On the other hand, Human Resources, Finance, and Sales are the departments that employees tend to leave more often. Interestingly, the department with the lowest score, indicating the highest turnover, is also Development.

![7](https://github.com/user-attachments/assets/31dd9304-8eaf-40d7-9be0-c657499bef6b)






