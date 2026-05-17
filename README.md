# Bookstore API

A RESTful API for a bookstore built with Node.js, Express, and MongoDB.

## Technologies
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- dotenv
- nodemon

## Run Locally

1. Clone the repo
2. Run `npm install`
3. Create `.env` file with:
```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```
4. Run `npm run dev`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /books | Get all books |
| GET | /books/:id | Get book by ID |
| POST | /books | Add a new book |
| PUT | /books/:id | Update a book |
| DELETE | /books/:id | Delete a book |

## Sample Request (POST /books)

```json
{
    "title": "Atomic Habits",
    "author": "James Clear",
    "price": 20,
    "isbn": "1234567890",
    "publishedDate": "2018-10-16"
}
```

## Sample Response

```json
{
    "_id": "64f1a2b3c4d5e6f7a8b9c0d1",
    "title": "Atomic Habits",
    "author": "James Clear",
    "price": 20,
    "isbn": "1234567890",
    "publishedDate": "2018-10-16T00:00:00.000Z",
    "createdAt": "2026-05-11T00:00:00.000Z",
    "updatedAt": "2026-05-11T00:00:00.000Z"
}
```

## Author
Qurat-ul-Ain — [github.com/ainieworks](https://github.com/ainieworks)
