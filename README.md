# 📚 Book Management API

A simple Express-based RESTful API built with **TypeScript** for managing books. It supports CRUD operations and CSV import functionality using `multer`. Jest is used for unit testing.

---

## 🚀 Features

- 📄 Add, update, delete, and list books
- 📥 Import books via CSV file
- 🧪 Unit tests for core functionality
- 🌐 MongoDB integration using Mongoose
- 🛡️ Type-safe code with TypeScript

---

## 🧰 Tech Stack

- **Backend**: Node.js, Express.js
- **Language**: TypeScript
- **Database**: MongoDB (via Mongoose)
- **File Uploads**: Multer
- **CSV Parsing**: Manual using `readline` and `fs`
- **Testing**: Jest

---

## 🔧 Setup Instructions

### 1. Clone the Repository


git clone https://github.com/your-username/book-management-api.git
cd book-management-api

### 2. Install Dependencies
npm install

### 3. Environment Variables
Create a .env file in the root directory and add:
PORT=5000
MONGO_URI=your_mongodb_connection_string

### 4. Run the Server (Dev Mode)
npm run dev
Server will start at: http://localhost:5000

📬 API Endpoints

| Method | Endpoint        | Description     |
| ------ | --------------- | --------------- |
| GET    | `/books`        | Get all books   |
| POST   | `/books`        | Add a new book  |
| PUT    | `/books/:id`    | Update a book   |
| DELETE | `/books/:id`    | Delete a book   |
| POST   | `/books/import` | Import CSV file |

### 📬 Postman Collection
You can test all API routes using the Postman collection provided:

[BookManagementAPI.postman_collection.json](./postman/BookManagementAPI.postman_collection.json)

🧪 Run Tests
npm test

🗃️ Sample CSV Format
title,author,publishedYear
The Alchemist,Paulo Coelho,1988
To Kill a Mockingbird,Harper Lee,1960

🙋‍♀️ Author
G Sri Vidya
Web Developer | DSA Enthusiast 


📄 License
This project is open source and available under the MIT License.


---

### ✅ Next Step: Push to GitHub

If this is your local folder:

```bash
git init
git add .
git commit -m "Initial commit - Book Management API"
git branch -M main
git remote add origin https://github.com/Sri-Vidya-Guttula/book-management-api.git
git push -u origin main




