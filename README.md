# E-Commerce Backend Challenge
  [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

  ## Description:
  This is the back end code for an e-commerce site that tracks products, tags, and categories. Started with a working Express.js API and configured it to use Sequelize to interact with a MySQL database.

  ## Table of Contents:
  * [User Story](#user-story)
  * [Acceptance Criteria](#acceprance-criteria)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Credits](#credits)
  * [License](#license)
  * [Video](#video)
  * [Questions](#questions)
  
  ## User Story
  AS A manager at an internet retail company
  * I WANT a back end for my e-commerce website that uses the latest technologies
  * SO THAT my company can compete with other e-commerce companies
  
  ## Acceptance Criteria
  GIVEN a functional Express.js API
  * WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
    * THEN I am able to connect to a database using Sequelize
  * WHEN I enter schema and seed commands
    * THEN a development database is created and is seeded with test data
  * WHEN I enter the command to invoke the application
    * THEN my server is started and the Sequelize models are synced to the MySQL database
  * WHEN I open API GET routes in Insomnia for categories, products, or tags
    * THEN the data for each of these routes is displayed in a formatted JSON
  * WHEN I test API POST, PUT, and DELETE routes in Insomnia
    ** THEN I am able to successfully create, update, and delete data in my database

  ## Installation
  Install NPM; Express; MySQL2; Sequelize; dotenv

  ## Usage:
  To run/test this application enter the "Develop" folder in the command line, start your MySQL server, source the schema.sql file by entering "source db/schema.sql" to create the ecommerce_db database. Confirm that the database was created by typing "show databases" into the MySQL server. Once you've confirmed that the database was created, type "exit" to exit your MySQL server. Now seed your database with the test data by entering "npm run seed" in the command line (must be in the Develop folder still). The command line will confirm that you have seeded your database with console logs. Now start your server by entering "npm start" in the command line. Once your server is started, navigate to Insomia to test the different api get, post, put, and delete routes:
  * localhost:3001/api/products - get, post
  * localhost:3001/api/products/:id - get, put, delete
  * localhost:3001/api/tags - get, post
  * localhost:3001/api/tags/:id - get, put, delete
  * localhost:3001/api/categories - get, post
  * localhost:3001/api/categories/:id - get, put, delete
  

  ## Credits:
  Starter code provided by UofU Bootcamp Course.

  ## License:
  Unlicense

  ## Contributing:
  https://www.contributor-covenant.org/

  ## Video:
  

  ## Questions:
  [My Github Account](https://github.com/kaileymorter)

  If you have additional questions about this project, please reach me at: k_morter@outlook.com
