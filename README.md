# LIBRARY MANAGEMENT WEB APPLICATION 

The library management system must allow a librarian to track books and their quantity, books issued to members, book fees.
 
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
         
 ## The pictures of the page are attached in images::
 
 
         
