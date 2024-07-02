# Jokes API

A simple RESTful API for creating, reading, updating, and deleting jokes.

## Usage

### Create a new joke

**Request:**
- **Method:** POST
- **URL:** `/api/jokes/new`

### find All Jokes

**Request:**
- **Method:** GET
- **URL:** `/api/jokes`

### find One Single Joke

**Request:**
- **Method:** GET
- **URL:** `/api/jokes/:id`

### update Existing Joke

**Request:**
- **Method:** PUT
- **URL:** `/api/jokes/update/:id`

### delete An Existing Joke

**Request:**
- **Method:** DELETE
- **URL:** `/api/jokes/delete/:id`

## Technologies
- Node.js
- Express
- MongoDB
- Mongoose
