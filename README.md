# e-commerce-back-end

This is a mysql database and back end for an ecommerce website. 

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Demonstration

Setup and Start: https://drive.google.com/file/d/1F1W3V32HL63pJKOEA0F__gywXuJkjIur/view

Insomnia Core Testing: https://drive.google.com/file/d/1r3wzTZPumVJ2_gzfS1h8oMUn6nHnNZut/view

## Installation and Usage

`npm i`

`mysql -u root -p`

Enter your password.

Inside mysql: `source db/schema.sql`, `quit`

`npm run seed`

`npm start`

## Repository

https://github.com/HunterHarvell/e-commerce-back-end.git