# 📚 Book API

A simple RESTful API built with **Node.js** and **Express** to manage a list of books (stored in memory).

## 🚀 How to Use

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

3. Use Postman to test the following endpoints:

### Endpoints

- `GET /books` – List all books
- `POST /books` – Add a new book `{ "title": "...", "author": "..." }`
- `PUT /books/:id` – Update a book by ID
- `DELETE /books/:id` – Remove a book by ID

Books are stored in memory and reset when the server restarts.

---
Happy coding! 🎉
