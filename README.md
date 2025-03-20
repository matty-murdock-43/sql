# SQL

Basics

1. Create database demo;
-- What is a database? - Container that stores data
-- Relational database? Data stored in the db is related to one another

2. Create table table_name(
//col_names
product_code int,
product_name varchar(max_length),
price float,
release_date date
)  

insert into products (product_code, product_name, price, release_date) values (1, 'productA', 1234, to_date('20-2-2025','dd-mm-yyyy'));

It's always better to use to_date function [piece of code that returns something] while adding date to a table
