# Node REST API Project

For this project, you will be creating a database, a server application and a client application. The client should be able to create, read, update and delete (CRUD) data in the database via a server API. 

You may use either SQL (PostgreSQL) or NoSQL (MongoDB) for your database.

## Database
### PostgreSQL Requirements (if not using MongoDB)
    1. Have at least three entities
    2. Have one to one, one to many and many to many relationships
    3. Have a SQL script that initializes the database

### MongoDB Requirements (if not using PostgreSQL)
    1. Have multiple collections
    2. There must be at least one relationship between two documents
    3. Utilize a nested schema

## Server Requirements 
    1. Use Express to create CRUD routes that respond with JSON
    2. Implement server-side logging (hint: use middleware!)
    3. Sending rendered static views (such as with EJS or Pug) is optional, but would be in addition to sending JSON
    4. Server must handle errors appropriately
    5. Each endpoint must be documented in the project's `README.md` file. Research documentation for public APIs (such as Imgur) for examples. 

## Client Requirements
The primary purpose of this project is creating a server API. To demonstrate that the server API works you should also build a small client app that uses Axios or `node-fetch` that can do CRUD operations on the database with it. This application would be run from the command line. 


Our next project will be building a front-end application using React.js that will take the place of this client app.