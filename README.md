# EvolentHealthContactInfoApp
Implementation of  production ready application for maintaining contact information.

# Software Requirements
1) .net Framework 4.2(Visual studio 12)
2) MS SQL severe 2012

# Technology used: 
1) MVC
2) WebAPI
3) Entity Framework
4) MS SQL

# Instruction
1) Pull the source code from Github
2) Execute SQL Scripts to create database and tables.Please SQL script @ ~\Evolent\EvolentHealthContactMaster\SQL
3) Change the connection string in .config files to connect to your database.
3) Run the application.
Use following links after running the application for CRUD operation -
Add contact :- http://localhost:5329/contact/create
Edit contact :- http://localhost:5329/contact/Edit/1
List contact :- http://localhost:5329/contact
Delete contact :- http://localhost:5329/contact/Delete/1
