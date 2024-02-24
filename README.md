# Blog App

The Blog App is a straightforward platform that combines various technologies. Here are the key components:

## Frontend Interface

The user interface is built using EJS, a powerful templating engine that allows dynamic content rendering. EJS enables us to create dynamic HTML pages by embedding JavaScript code directly into our templates.

## Backend Logic

The core functionality of the app is powered by Node.js and Express.js. These technologies handle routing, middleware, and server-side logic. Express.js provides a robust framework for building RESTful APIs and handling HTTP requests.

## Database Management

We utilize MongoDB as our database system, and Mongoose acts as the ODM (Object-Document Mapper). Mongoose simplifies interactions with MongoDB by providing a schema-based solution. This allows us to define data models, perform CRUD operations, and manage relationships between different data entities.

## MVC Architecture

To maintain a clean and organized codebase, we follow the Model-View-Controller (MVC) architecture.

## Requirements
+ node.js
+ mongodb with atlas setup [Atlas](https://www.mongodb.com/atlas/database)
    + try free cluster
    + create new database
    + add blogs collection
    + get connection string to the database you have created
    + save it to environment variables
    + check user access permissions from Database Access,<br>and update as required.
+ GIT
## Available Scripts

In the project directory, you can run:
### `npm install` to install required dependencies
### `nodemon app` to run the app

Open [localhost:3000](http://localhost:3000) to view it in your browser.