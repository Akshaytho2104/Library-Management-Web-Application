# LIBRARY MANAGEMENT WEB APPLICATION 

The library management system must allow a librarian to track books and their quantity, books issued to members, book fees etc.

Below mentioned Parameter are Created in Library Management System:
 
  **Members**
   * Add Member
    
  **Books**
   * Add New Book
   * Import Book From API    (Frappe API: https://frappe.io/api/method/frappe-library?)
     
  **Reports**
   * Most Popular Books
   * Highest Paying Customers
   
  **ransaction**
   * Issue Book to users online.
   
   
## The use cases included here are to:

* Perform general CRUD operations on Books and Members
* Issue a book to a member
* Issue a book return from a member
* Search for a book by name and author
* Charge a rent fee on book returns
* Make sure a member’s outstanding debt is not more than Rs.500

## Technology used

         Flask (python framework)
         Python (For Backend)
         HTML   (For Frontend)
         MySQLdb (For Database)
         XAMPP Server 
         
## Important Library
         
         pip3 install flask
         from flask import Flask, render_template, flash, redirect, url_for, request
         from flask_mysqldb import MySQL
         from wtforms import Form, validators, StringField, FloatField, IntegerField, DateField, SelectField
         from datetime import datetime
         import MySQLdb
         import urllib
         import requests
         
 ## The picture of MySQL DATABASE
 
 ![Screenshot (42)](https://user-images.githubusercontent.com/58549996/151511797-e51238e4-a865-4ea4-a7c2-6e1635e59fde.png)
 
 
 ## Web Applications Pitures:
 
 
 
 ![image](https://user-images.githubusercontent.com/58549996/151510097-37c238ca-5361-4fe8-afa7-4bc690067c83.png)
 ![image](https://user-images.githubusercontent.com/58549996/151711062-d4110784-97a8-4c5a-a523-524f2318c84c.png)
![image](https://user-images.githubusercontent.com/58549996/151510155-acaa064b-988e-4601-bbc5-b90edb620253.png)
![image](https://user-images.githubusercontent.com/58549996/151510207-295c3425-97b5-4622-9954-20b6ea48270a.png)
![image](https://user-images.githubusercontent.com/58549996/151711087-3c23bf35-9894-4ee8-b872-e80f1997cc44.png)
![image](https://user-images.githubusercontent.com/58549996/151711166-2a17e5bf-6343-4d86-b24c-c49430d340ea.png)




         
