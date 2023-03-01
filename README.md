# sql-challenge


     A research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

     This Challenge is divided into three parts: data modeling, data engineering, and data analysis.

1. Data Modeling:
All CSV files presented in "data" folder has been inspection and the Relationship Diagram of the tables has been created and placed in "employeeSQL" folder.

2. Data Engineering:
Using the provided information, a table schema for each of the six CSV files has been created. 
Tables.sql file of the table schemata has been created and placed in "employeeSQL" folder.
Each CSV file has been imported into its corresponding SQL table.

3. Data Analysis:
Queries.sql file has been created and placed in "employeeSQL" folder. This file contains a set of queries that correspond to the following conditions:

   * List the employee number, last name, first name, sex, and salary of each employee.

   * List the first name, last name, and hire date for the employees who were hired in 1986.

   * List the manager of each department along with their department number, department name, employee number, last name, and first name.

   * List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

   * List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

   * List each employee in the Sales department, including their employee number, last name, and first name.

   * List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

   * List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).