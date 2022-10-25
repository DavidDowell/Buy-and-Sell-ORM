# Buy-and-Sell-ORM

## Application Objective

As a manager at an internet retail company it is important to have state of the art
technologies to compete with other e-commerce companies. This application provides the back-end
technology to provide the manager with what they need.

## How it Works

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

## How to Start

* In the command line, initialize with "npm init"
* Check the package.json for your dependencies: dotenv, express, mysql2, sequelize
* If they are all contained in the package.json, run "npm install"
* Make sure there is a .env file at the root of repo, add DB_NAME = ecommerce_db, DB_USER = mysql username, DB_PW = mysql password.
* Once everything is installed, make sure your MySQL server is on and log into mysql "mysql -u root -p" in the command line
* Type "USE ecommerce_db;" and then "source db/schema.sql" into the command line to connect to the database and initialize.
* Quit out of mysql "quit;"
* Start the server "npm start"
* Seed the database "npm run seed"
* Create routes (GET, CREATE, UPDATE, DELETE) in Insomnia for the models as shown in the walkthrough and test them.

## Walkthrough



## Github Repository

https://github.com/DavidDowell/Buy-and-Sell-ORM