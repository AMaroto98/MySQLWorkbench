
# MySQLWorkbench

## Relational diagram

Here we have the relational model of a store that sells books.

![RelationalDiagram](/images/Diagrama.png)

---

## Create Script

After designing the model in MySQLWorkbench it has to be exported.

To do this go to File --> Export --> Forward Enginner SQL CREATE Script

![StepOne](/images/Export.png)

We choose a name for the script.

![StepTwo](/images/ScriptName.png)

We choose if we want any additional option

![StepThree](/images/Filter.png)

Before finishing, we have a preview of the file in case we want to modify anything else.

![StepFour](/images/Preview.png)

The final result can be seen in Script.sql

---

## Import database

To import a database already created in MySQL Workbrench we can follow the following steps:

1. Go DataBase --> Reverse Engineer

![StepOne](/images/1.png)

2. We connect to the database server, in my case MySQL server

![StepTwo](/images/2.png)

3. Select the database to be imported. I will import Northwind.

![StepThree](/images/3.png)

4. Done

![StepFour](/images/4.png)
