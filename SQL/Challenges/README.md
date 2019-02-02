# Challenges

Julia asked her students to create some coding challenges. Write a query to print the hacker_id, name, and the total number of
challenges created by each student. Sort your results by the total number of challenges in descending order. If more than one 
student created the same number of challenges, then sort the result by hacker_id. If more than one student created the same number
of challenges and the count is less than the maximum number of challenges created, then exclude those students from the result.

**Input Format**

The following tables contain challenge data:

Hackers: The hacker_id is the id of the hacker, and name is the name of the hacker.

|Column|	Type|
|---|---|
|hacker_id|	Integer|
|name	|String|

Challenges: The challenge_id is the id of the challenge, and hacker_id is the id of the student who created the challenge.

|Column|	Type|
|---|---|
|challenge_id|	Integer|
|hacker_id|	Integer|

**Sample Input 0**

Hackers Table:

|_hacker_id_|_name_|
|---|---|
|5077|Rose|
|21283|Angela|
|62743|Frank|
|88255|Patrick|
|96196|Lisa|


Challenges Table:

|_challenge_id_|_hacker_id_|
|---|---|
|	61654|5077 |
|	58302|21283|
|	40587|88255|
|	29477|5077 |
|	1220 |21283|
|	69514|21283|
|	46561|62743|
|	58077|62743|
|	18483|88255|
|	76766|21283|
|	52382|5077 |
|	74467|21283|
|	33625|96196|
|	26053|88255|
|	42665|62743|
|	12859|62743|
|	70094|21283|
|	34599|88255|
|	54680|88255|
|	61881|5077 |


**Sample Output 0**

|hacker_id|name|total|
|---|---|---|
|21283 |Angela |6|
|88255 |Patrick|5|
|96196 |Lisa   |1|

