# Movie CRUD API (Node.js + MongoDB Atlas)

This is a RESTful API built using **Node.js**, **Express.js**, and **MongoDB Atlas** that allows users to Create, Read, Update, and Delete (CRUD) movie data.

---

## Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Postman (for testing)

---

## 📁 Project Setup

### 1. Clone the repository

```bash
git clone https://github.com/sagarranaa/credenceanalytics.git
cd credenceanalytics
```

### 2. Install dependencies

npm install

### 3. Configure environment variables

Create a .env file in the root folder and add:
MONGO_URI=<your-mongodb-connection-uri>
Running the Server
node index.js

### 4.API Endpoints (Test in Postman)

Base URL: http://localhost:3000/movies
Method Endpoint Description
POST / Create a new movie
GET / Get all movies
GET /:id Get a movie by ID
PUT /:id Update a movie by ID
DELETE /:id Delete a movie by ID

{
"name": "Avengers: Endgame",
"img": "https://bit.ly/2Pzczlb",
"summary": "Adrift in space with no food or water..."
}
