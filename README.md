# Student CRUD API – Node.js, Express, PostgreSQL

This project is a simple CRUD (Create, Read, Update, Delete) API for managing student records.  
It was built using **Node.js**, **Express**, and **PostgreSQL**, and tested using **Postman**.

---

## Features

- Create new students
- Retrieve all students
- Retrieve a single student by ID
- Update student information
- Delete a student
- PostgreSQL database integration with parameterized queries

---

## Technologies Used

- Node.js
- Express.js
- PostgreSQL
- pg (node-postgres)
- dotenv

---

## Setup Instructions

### 1. Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git

shell
Copy code

### 2. Install dependencies
npm install

shell
Copy code

### 3. Create a `.env` file
DB_USER=your_user
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
DB_NAME=your_dbname

shell
Copy code

### 4. Start the server
npm start

yaml
Copy code

---

## API Endpoints

| Method | Endpoint             | Description                |
|--------|-----------------------|----------------------------|
| GET    | /students             | Get all students           |
| GET    | /students/:id         | Get student by ID          |
| POST   | /students             | Create a new student       |
| PUT    | /students/:id         | Update student info        |
| DELETE | /students/:id         | Delete a student           |

---

## Notes

This project was built while following a tutorial as part of my learning process.  
Additional improvements or extensions may be added in the future.