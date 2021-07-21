# Employee Database: A Mystery in Two Parts
You have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files. You will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. 
### Data Modeling
* Inspect the CSVs and sketch out an ERD of the tables.
<p align="center">
<img src="https://github.com/toshitorihara/sql-challenge/blob/main/images/ERD_final.png" height="75%" width="75%">
</p>

### Data Engineering
* Use the information you have to create a table schema for each of the six CSV files. 
* Import each CSV file into the corresponding SQL table.

### Data Analysis
1. List the following details of each employee: employee number, last name, first name, sex, and salary.
2. List first name, last name, and hire date for employees who were hired in 1986.
3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
4. List the department of each employee with the following information: employee number, last name, first name, and department name.
5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Submision
* Create an image file of your ERD. (ERD_final.png)
* Create a .sql file of your table schemata. (schema_final.sql)
* Create a .sql file of your queries. (query_final.sql)
* (Optional) Create a Jupyter Notebook of the bonus analysis. (employee_final.ipynb)
* Create and upload a repository with the above files to GitHub and post a link on BootCamp Spot.
* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file
