## C13 E-commerce back end

## Table of Contents

* [Description](#Description)
* [Guidelines](#Guidelines)
* [Installation](#Installation)
* [Usage](#Usage)
* [Snips](#Snips)
* [Links](#Links)
* [Questions](#Questions)

## Description

This is the backend code for an e-commerce website with a mysql database. 

## Guidelines
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Installation

In your command terminal:

1. npm install

## Usage
Right click schema file and open terminal

1. mysql -u root -p
2. enter password when prompted
3. source schema.sql

Right click main server.js file and open terminal

1. npm run seed
2. npm start

## Snips

Command line clip:



Insomnia Clip:



## Links

https://github.com/DakMorg/c13

## Questions

If you have any questions...

Here is a link to my github profile.
https://github.com/DakMorg

Here is my email address. 
morgandakota41100@gmail.com