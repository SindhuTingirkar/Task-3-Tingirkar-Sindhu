# Project 3: Database Integration

## Overview

This project was developed as part of the DecodeLabs Full Stack Development Industrial Training Kit. The objective of this project is to integrate a backend application with a relational database and perform CRUD (Create, Read, Update, Delete) operations.

## Technologies Used

* Node.js
* Express.js
* MySQL
* MySQL2
* CORS
* Postman

## Features

* Database integration using MySQL
* RESTful API development
* Create new users
* Retrieve all users
* Update existing user information
* Delete users from the database
* Parameterized SQL queries for security

## Database Schema

### Users Table

| Field | Type         | Constraints                 |
| ----- | ------------ | --------------------------- |
| id    | INT          | PRIMARY KEY, AUTO_INCREMENT |
| name  | VARCHAR(100) | NOT NULL                    |
| email | VARCHAR(100) | UNIQUE, NOT NULL            |
| age   | INT          | CHECK(age >= 18)            |

## API Endpoints

### Create User

POST /users

### Get Users

GET /users

### Update User

PUT /users/:id

### Delete User

DELETE /users/:id

## Installation

1. Clone the repository.
2. Install dependencies:

npm install

3. Create MySQL database and users table.
4. Update database credentials in db.js.
5. Start the server:

node server.js

## Output

The application successfully performs all CRUD operations and stores user information in MySQL.

## Learning Outcomes

* Database integration
* REST API development
* SQL operations
* Backend development using Express.js
* Secure database interactions using parameterized queries
