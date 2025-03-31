# GoFlix-API 🎬

A simple REST API built with **Golang** and **gorilla/mux** for managing movie records. This API allows users to **create, read, update, and delete (CRUD)** movies with details like title, director, and ISBN.

## Features ✨
- Fetch all movies 🎥
- Retrieve a single movie by ID 🔍
- Add a new movie ➕
- Update an existing movie ✏️
- Delete a movie ❌

## Technologies Used 🚀
- **Golang** (Backend logic)
- **gorilla/mux** (Routing)
- **net/http** (HTTP server)
- **math/rand** (Generating random IDs)
- **encoding/json** (Data serialization)

## Installation 🛠️

### Prerequisites
Make sure you have **Go** installed on your system. If not, download it from [golang.org](https://golang.org/dl/).

### Steps
```sh
# Clone the repository
git clone https://github.com/pradyumnajavalagi/GoFlix-API.git

# Navigate to the project directory
cd GoFlix-API

# Install dependencies
go mod tidy

# Run the API
go run main.go
```

## API Endpoints 🌍

| Method | Endpoint         | Description |
|--------|-----------------|-------------|
| GET    | `/movies`       | Get all movies |
| GET    | `/movies/{id}`  | Get a single movie by ID |
| POST   | `/movies`       | Create a new movie |
| PUT    | `/movies/{id}`  | Update an existing movie |
| DELETE | `/movies/{id}`  | Delete a movie |

## Example Movie JSON Object 📜
```json
{
  "isbn": "438-1234567890",
  "title": "Movie One",
  "director": {
    "firstname": "John",
    "lastname": "Doe"
  }
}
```

## Contributing 🤝
Feel free to open an issue or submit a pull request if you'd like to improve this project!

## License 📜
This project is **MIT licensed**.

---
Made by [Pradyumna A J](https://github.com/pradyumnajavalagi)

