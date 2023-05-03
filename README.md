# HR Project

This repository contains an analysis of HR data for a company. The analysis was done using SQL queries on a MySQL database. The following steps were taken:

1.	Creating the Database: A new database called "hrproject" was created, which was used for the analysis by selecting data from the "hrsql" table.

2.	Renaming Columns: The name of the "id" column was changed to "emp_id".

3.	Checking Table Structure: The structure of the "hrsql" table was checked using the "describe" command, and specific columns were selected to view.

4.	Cleaning and Formatting Data: The "birthdate", "hire_date", and "termdate" columns were cleaned and formatted to be in the "date" format using the "update" and "alter table" commands.

5.	Adding New Column: A new column "age" was added to the table using the "alter table" and "update" commands.


6.	Using Aggregate Functions: Aggregate functions such as "min", "max", "count", and "avg" were used to answer various questions about the data such as age distribution, gender breakdown, and job title distribution.

7.	Grouping and Sorting Data: The "group by" and "order by" clauses were used to group and sort data based on various criteria.

8.	Calculating Turnover Rate: The turnover rate for each department was calculated by joining and grouping data from the "hrsql" table.

9.	Analyzing Employee Count Over Time: The company's employee count over time was analyzed based on hire and term dates using the "group by" clause to group data by year and the "sum" function to aggregate the number of hires and terminations.

## Conclusion

In conclusion, this analysis provides valuable insights into HR data for the company. It showcases the use of SQL queries to manipulate and analyze data, and the results can be used to make informed decisions regarding the company's HR policies.
