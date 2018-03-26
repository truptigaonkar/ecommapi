# Laravel E-Commerce Restful API

An Ecommerce Restful API using Laravel API Resource (Laravel Version 5.6, PHP version 7.2).

Features:
1.	Setting up the environment.
2.  Creating Model, Factory, Migtation for Products and Reviews.
3.	Creating API Resource Controller for Products : List,Show,Store,Update,Delete Products
4.	Creating API Resource Controller for Reviews : List,Show,Store,Update,Delete Reviews
5.	Setup migration to create tables Products & Reviews.
6.  Database seeding with faker library and factory for Products & Reviews.
7.  Creating one-many relationship between Product and Review.
8.  Transform product & Review model for your API.
9.  Setup environment in Postman.
10. Implement meta links in API.
11.  Configure API Authentication - Passport package to provide authentication
	- Authenticated users can store/update/delete Products
	- Normal users can List/Show Products and List,Show,Store,Update,Delete Reviews
12.	Pagination feature is available on Products list.   
13.	MYSQL dump of the database named ecommapi.sql’ is provided.
    

### Prerequisites

•	Knowledge of Laravel php framework
•	XAMPP (start MySQL, Apache service)
•	Phpmyadmin 
•	Php laravel (Laravel Framework 5.6, PHP version 7.2)
•	Text editor (Visual Studio Code)
•	Postman tool

## Getting Started

Step 1: Download and add the folder inside ‘C:\xampp\htdocs’

Step 2: Open phpmyadmin http://localhost/phpmyadmin/index.php , create database ‘ecommapi’ and import database dump file ‘ecommapi.sql’ into it.

Step 3: Go to command prompt

c:\xampp\htdocs\ecommapi>php artisan serve 

Use Postman tool for performing integration testing with your API.



