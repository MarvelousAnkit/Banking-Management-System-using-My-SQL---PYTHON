# Banking-Management-System-using-My-SQL---PYTHON
About
__________
In this project we have created a Virtual Bank (COLONY BANK OF INDIA) using Python and MySQL. Data entered by the user are stored in MYSQL database in tabular form. Here  We have done CRUD Operation. The Best Part of this code is that it is 100 % user friendly because of excess use of exceptional handling.

This project is designed for The Bank Staffs to keep the record of their customers. Only authorized Users can have the accessibility to the program. User after Logging in have the support to display all records, and modify it accordingly. If someone is not having Login Id, password he/she could make a new id. Further it can also check overall record of a local customer or full detail of a single a/c as per transactions, create a new record for new customer, Update an old customer record, Delete a record of a customer and Update Loans of the customer. Python is used as Front End and MySQL is used as Back End.

*Requirement
______________________________ 

1) Python Latest Version 
2) Visual Code
3) Mysql
4) Python My SQL Converter : Most Important

*Module Used In python Code
______________________________

1) datetime
2) mysql.connector

*About Mysql Code
__________________________

1) Database used here is Hubnet
2) address = local
3) user=root
4) password=12345678
 
UserName is the Primary Key in Bank Table  and UserName1 is the Foreign key in  Transaction Table.

Suggestion: Run Bank-Project.py Code in IDLE.

Before Running This Code in Your System Make Sure you have created the bank and transactions Table.

*My Sql Code for Creating Table Bank
create table bank(name varchar(30), UserName varchar(30),password tinytext , Date_of_birth date, address varchar(40) ,Mobile_Number varchar(30) ,Aadhar_no varchar(30), Balance int);

*My Sql code for creating Table Transaction:
create table Transaction(credited int , debited int , username1 varchar(20), foreign key(username1) references bank(username));

Some Glimpse of this project are shown below
__________________________________________________


<img width="960" alt="DEMO1" src="https://user-images.githubusercontent.com/110014127/187087816-6f230993-c3f2-4816-baa9-1834c84bf2d1.png"><img width="960" alt="DEMO2" src="https://user-images.githubusercontent.com/110014127/187087821-5ae8a0b6-dcf3-463d-a492-da88e3d65447.png"><img width="960" alt="DEMO3" src="https://user-images.githubusercontent.com/110014127/187087834-994a3814-2f92-49dd-a6a5-d56422d92027.png">


<img width="960" alt="DEMO4" src="https://user-images.githubusercontent.com/110014127/187087837-6e3e3e7b-a110-4eef-9479-426511fb55f3.png">

<img width="960" alt="DEMO5" src="https://user-images.githubusercontent.com/110014127/187087843-c6a1af98-d81f-4a99-ae44-8a7853130eeb.png">

Properties of Table In MY SQL Database:
___________________________________________

<img width="960" alt="MY SQL DATABASE" src="https://user-images.githubusercontent.com/110014127/187087967-35e7bbb6-219e-4eb5-8238-a3e90b006e8b.png">
