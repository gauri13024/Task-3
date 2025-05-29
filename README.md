# Task-3

📚 Book API (Node.js + Express)
🔧 Description
This is a simple RESTful API built using Node.js and Express.js to manage a list of books. It supports basic CRUD operations (Create, Read, Update, Delete) and stores book data in-memory (no database required). This project is ideal for beginners learning how REST APIs work and how to use Postman for API testing.

🚀 Features
GET /books – Retrieve all books

POST /books – Add a new book (with title and author)

PUT /books/:id – Update a book's title or author by ID

DELETE /books/:id – Delete a book by ID

🛠 Technologies Used
Node.js

Express.js

Postman (for API testing)

In-memory array (for temporary data storage)

📂 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/book-api.git
cd book-api
Install dependencies:

bash
Copy
Edit
npm install
Start the server:

bash
Copy
Edit
node index.js
Open Postman and test the API at:

bash
Copy
Edit
http://localhost:3000/books
