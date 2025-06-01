# Book API


npm install
node server.js
Server: http://localhost:3000

 Endpoints
GET /books – Get all books

POST /books – Add a new book
Body: { "title": "Book Title", "author": "Author Name" }

PUT /books/:id – Update a book by ID
Body: { "title": "New Title", "author": "New Author" }

DELETE /books/:id – Delete a book by ID
