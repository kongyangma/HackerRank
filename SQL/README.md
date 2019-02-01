# Projects

You are given a table, Projects, containing three columns: Task_ID, Start_Date and End_Date. It is guaranteed that the difference 
between the End_Date and the Start_Date is equal to 1 day for each row in the table.

| Column | Type |
| --- | --- |
| Task_ID | Integer |
| Start_Date | Date |
| End_Date | Date |


If the End_Date of the tasks are consecutive, then they are part of the same project. Samantha is interested in finding the total 
number of different projects completed.

Write a query to output the start and end dates of projects listed by the number of days it took to complete the project in ascending 
order. If there is more than one project that have the same number of completion days, then order by the start date of the project.

Sample Input

| Task_ID | Start_Date | End_Date |
| --- | --- | --- |
| 1 | 2015-10-01 | 2015-10-02 | 
| 2 | 2015-10-02 | 2015-10-03 |
| 3 | 2015-10-03 | 2015-10-04 |
| 4 | 2015-10-13 | 2015-10-14 |
| 5 | 2015-10-14 | 2015-10-15 |
| 6 | 2015-10-28 | 2015-10-29 |
| 7 | 2015-10-30 | 2015-10-31 |


Sample Output

| Start_Date | End_Date |
| --- | --- |
|2015-10-28 | 2015-10-29|
|2015-10-30 | 2015-10-31|
|2015-10-13 | 2015-10-15|
|2015-10-01 | 2015-10-04|
