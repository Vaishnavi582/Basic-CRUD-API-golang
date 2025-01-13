
# Basic CRUD API with Golang

This project is a simple implementation of a CRUD (Create, Read, Update, Delete) API built using Go. It provides endpoints for managing resources (e.g., users, products, or any entity) with basic operations.

## Features

- Get all movies: Retrieve the list of all movies.
- Get a movie by ID: Fetch details of a specific movie using its unique ID.
- Create a movie: Add a new movie to the collection.
- Update a movie: Modify the details of an existing movie.
- Delete a movie: Remove a movie from the collection.

## Technologies
- **Go (Golang):** The main programming language.
- **Gorilla Mux:** A powerful HTTP router and URL matcher for building APIs.
- **JSON:** Data is encoded and decoded in JSON format.

## Endpoints
| Method | Endpoint       | Description              |
|--------|----------------|--------------------------|
| GET    | /movies        | Retrieve all movies      |
| GET    | /movies/{id}   | Retrieve a movie by ID   |
| POST   | /movies        | Create a new movie       |
| PUT    | /movies/{id}   | Update an existing movie |
| DELETE | /movies/{id}   | Delete a movie by ID     |
