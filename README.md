This repository contains multiple examples on how SQL Server can be used to manipulate strings.

List of examples:
1) Adding and Subtracting Days, Months and Years to a date using function DATEADD.
2) Calculate first day, last day and second to last day of the current month using functions GETGATE, DAY, MONTH, DATEADD, DATEDIFF, EOMONTH and date 1900-01-01 (default value for SQL Server's data type DATETIME).
3) Counting the number of business days between 2 dates using function GENERATE_SERIES.
4) Counting the number of days between 2 dates using function DATEDIFF.
5) Counting the number of days between hiring days between current row and next record using the window function LEAD.
6) Counting the number of days in a year using functions GETDATE, DATEADD, DATEDIFF.
7) Counting the number of employees hired every month of every year using function GENERATE_SERIES, DATETIME functions and AGGREGATION functions.
8) Counting the number of occurrences for every weekday in a year using function GENERATE_SERIES.
9) Creating a calendar for current month using function GENERATE_SERIES, DATE functions, AGGREGATION functions, pivoting via CASE statements
10) Retrieving dates of a specific weekday in a year using function GENERATE_SERIES.
11) Retrieving dates of first and last occurrences for a specific weekday in a month using function GENERATE_SERIES.
12) Retrieving start and end dates for a specific quarter using functions MODULUS (%), DATEADD, MONTH, DAY, CAST, LEFT and UNION ALL operator.
13) Retrieving start and end dates for all 4 quarters in a year using functions DATEADD, DATEDIFF, DAY, QUARTER, YEAR, GETDATE and 1 iteration.
14) Retrieving the list employees that were hired on the same date along with at least other 4 employees using a Cartesian Product, DATETIME functions and COUNT function.
