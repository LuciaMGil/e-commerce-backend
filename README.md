# Object-Relational Mapping (ORM): E-commerce Back End
The purpose of this application is to create the back end for an e-commerce website. The app was built using Sequelize, MYSQL2, dotenv and Express.


## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)



# Installation
npm init

npm install mysql2

npm install sequelize

npm install dotenv

Add a .env file to the root of the app with information for the following variable:

DB_NAME: 'ecommerce_db'
DB_USER:'root'
DB_PW: 'Your_password'

# Usage 

In bash termal:

1. Type:  mysql -u root -p

2. Enter your password

3. Type:  source db/schema.sql

4. Type: quit

5. Type: npm run seed

6. Type: npm run start
