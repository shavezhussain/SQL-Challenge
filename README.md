# SQL Challenge - Pewlett Hackard Employee Database

This repository contains the SQL Challenge project for Pewlett Hackard, a fictional company. In this project, we work with a dataset from the 1980s and 1990s, involving data modeling, data engineering, and data analysis using SQL.

## Background

As a data engineer at Pewlett Hackard, your primary task is to conduct a research project about employees who worked at the company during the 1980s and 1990s. This project involves:

- Data Modeling: Creating an Entity Relationship Diagram (ERD) or table schemas for the database.
- Data Engineering: Designing and creating the database tables, including defining data types, keys, and relationships. Importing data from CSV files into these tables.
- Data Analysis: Answering specific questions about the employee data using SQL queries.

## Repository Structure

The repository is organized as follows:

- **ERD**: This directory contains the Entity Relationship Diagram (ERD) or table schemas for the database tables. You can find the schema design in the `schema.png` file.

- **SQL**: This directory contains the SQL script used to create the database schema and perform data analysis. The script is named `pewlett_hackard.sql`.

- **Data**: This directory holds the CSV files with the employee data used in the project.

- **README.md**: The README file provides an overview of the project, instructions, and details about the SQL queries used for data analysis.

## Instructions

To set up and work with this project, follow these steps:

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/shavezhussain/sql-challenge.git
   ```

2. Navigate to the project directory.

   ```bash
   cd sql-challenge
   ```

3. Create your database and tables by running the SQL script in your preferred database management tool.

   ```bash
   psql -d your_database_name -a -f SQL/pewlett_hackard.sql
   ```

4. Import the data from the provided CSV files into the respective tables using SQL.

5. Use the SQL queries in the script to perform data analysis tasks as outlined in the project instructions.

6. Explore the results and use them for your analysis.

## Data Analysis

The SQL queries in the `pewlett_hackard.sql` script address various data analysis tasks, including:

- Listing employee details such as employee number, last name, first name, sex, and salary.
- Identifying employees hired in 1986.
- Listing department managers with department information.
- Associating each employee with their department.
- Finding specific employees by name and department.
- Analyzing the frequency of employee last names.

These queries provide insights into the Pewlett Hackard Employee Database.

## Credits

This project is part of a fictional scenario created for educational purposes. The data and company mentioned are entirely fictional.

## License

This project is available under the [MIT License](LICENSE). Feel free to use and modify the code for your own learning and projects.
