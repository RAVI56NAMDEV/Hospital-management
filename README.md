# Hospital-Management-System-Using-MySQL-and-tkinter
### DataBase Management System created with the help of MySQL workbench



This Project is created by using tkinter for GUI

- tkinter provides simple way to create GUI elements using Python
- tkinter toolkit contains various widgets for GUI
- Tk widgets can be used to construct buttons, menus, data fields, etc. in a Python application.

## Features:

- Relational DataBase Management System
- Contains a GUI with various input boxes which are used to input patient Information.
- There are buttons which can perform tasks like adding and deleting data from database table,clearing the input fields, updating the existing information in database,etc.
- Also , the buttons provide functionalities to fetch data and exit or quit the system.
- When the code is run , it gets connected with the MySQL database which is created in MySQL workbench.



## How to Use?


- Clone this repository
- Inside the "Hospital Management System create by ravi kumar" file there is a python file called "Hospital.py" which contains the whole source code.
- Open MySQL workbench and create the database with name "hospital"
- Inside the database create a table called "hosital" (ignore the spelling mistake)
- Create columns with appropriate names which are specified in the source code.
- Change the password field in the lines containing "sql.connect(...)" command.
- Run the code and make sure that your created Database is connected successfully.
- Now you can easily manage the patient information and can perform various operations.

# You need to create database like this 

mysql> desc hospital;
+-----------------+-------------+------+-----+---------+-------+
| Field           | Type        | Null | Key | Default | Extra |
+-----------------+-------------+------+-----+---------+-------+
| Nameoftables    | varchar(50)        | YES |         | NULL  |       
| ref             | varchar(45) | NO   | PRI | NULL    |       |
| Dose            | varchar(45) | NO   |     | NULL    |       |
| Numberoftablets | varchar(45) | NO   |     | NULL    |       |
| Lot             | varchar(45) | NO   |     | NULL    |       |
| Issuedate       | varchar(45) | NO   |     | NULL    |       |
| Expdate         | varchar(45) | NO   |     | NULL    |       |
| Dailydose       | varchar(45) | NO   |     | NULL    |       |
| StorageAdvice   | varchar(45) | NO   |     | NULL    |       |
| nhsNumber       | varchar(45) | NO   |     | NULL    |       |
| PatientName     | varchar(45) | NO   |     | NULL    |       |
| DOB             | varchar(45) | NO   |     | NULL    |       |
| PatientAddr     | varchar(45) | NO   |     | NULL    |       |
+-----------------+-------------+------+-----+---------+-------+
13 rows in set (0.01 sec)

# note: 
if you want to give all values as string it will work otherwise take specific data for datatype each row.

## GUI preview:
![image](https://user-images.githubusercontent.com/67269209/162787987-9b02a8da-382f-4a96-b594-b73ca459d308.png)



## Prerequesites:
- Basic Knowledge of SQL query Language.
- Fair understanding of Python Programming language.
- MySQL workbench preinstalled.
- Any python IDE for running the code.
