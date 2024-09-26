# Ecommercial sale website
A e-commercial sale website created with asp.net MVC and SQL Server.
## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#techonologies-used)
* [Features](#features)
* [Setup](#setup)
* [Project Status](#project-status)
## General Information
A website which supports the seller to sell electronic equipments and the customers to order and buy them.
## Techonologies Used
- .NET 8.0
- SQL Server 20
- Visual Studio 2022
## Features
1. Website management:
- Administrator (admin) manages theses objects: categories, brands, products, users and orders.
- Admin can see values of each object and add, update or delete them.
2. Product management:
- Add, update, delete products.
- Find products based on product's name, price range, category and brand.
- See a product in detail.
- Being able to update the quantity of products in stock when log in as admin.
- Find similar products automatically.
- Give the product rating after buying.
- Comment about product.
3. Buying management
- Each user has a cart, which becomes empty when they log out.
- At homepage, they can add products to the cart.
- At cart page, they can check products they have added and remove products from the cart.
- User can order and go to payment page. All products which was in cart are taken into the order. Finish payment will make the cart empty.
4. Order management
- Admin can see orders from the past.
- User can see orders which they ordered.
- Allow to follow the state of the order. After ordering, the state turns into "delivering" state. When the customer confirm receiving order, the order is finished.
5. User management
- User can register an account, which is a normal user account.
- Only one admin account.
- User can log in their user account.
- Have ability to update their personal information (avatar, name, phone number,...)
- User can review their orders from the past.
6. Payment
- There are two payment methods: by cash or by Paypal.
- When user would like to pay, they will be redirected to payment page which have buyer's name, date of purchase and allowed to choose which payment method they would like to use.
7. Statistic
- Admin can calculate revenue and number of products sold which is based on categories, brands and time (month, quarter, year).
## Setup
- To run this project, the first thing to do is to create database.
- Declare the equipment's server name and the database's name which user names by themselves in file appsetting.json. Fill in:
  "DefaultConnection": "Server=_server name_;Database=_database's name_;TrustServerCertificate=True;Trusted_Connection=True;MultipleActiveResultSets=true"
- In Package Manage Console, type "update-database" and enter. This will create a database in SQL Server, which have name declared.
- Choose a port to run (http, https, IIS Express...).
- Press F5 and run the web. 
## Project Status
- This project has completely finished.

