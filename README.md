# todo-tdd project

## Overview

This project is a RESTful API for managing Todo items, allowing users to create, read, update, and delete todos.
Built with Node.js and Express, it uses Mongoose to interact with a MongoDB database.

## Features

- Create new todos
- Retrieve a list of todos
- Retrieve a single todo by ID
- Update existing todos
- Delete todos
- Basic error handling and validation

## Technologies Used

- Node.js
- Express
- Mongoose
- MongoDB
- Jest
- Supertest (for testing)

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- MongoDB (running locally or using a cloud service)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-tdd.git
   cd todo-tdd

2. Install dependencies:

```bash

npm install
```
3. Set up your MongoDB connection:

   - Update the connection string in the mongodb.connect.js file to point to your MongoDB database.

4. Start the server:

```bash

    npm start ## starts server
    npm run test ## for testing
```
### API Endpoints

    POST /todos - Create a new todo
    GET /todos - Retrieve all todos
    GET /todos/
    - Retrieve a todo by ID
    PUT /todos/
    - Update a todo by ID
    DELETE /todos/
    - Delete a todo by ID



