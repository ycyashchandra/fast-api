# FastAPI Basic CRUD Project (Without a Database)

This is a simple CRUD (Create, Read, Update, Delete) API built using [FastAPI](https://fastapi.tiangolo.com/). It is designed for learning purposes and does not use any database. Instead, it stores data in memory.

## Features

- **Create**: Add new items to the in-memory storage.
- **Read**: Retrieve all items or a specific item by ID.
- **Update**: Modify an item by its ID.
- **Delete**: Remove an item by its ID.

## Requirements

- Python 3.7+
- FastAPI
- Uvicorn (optional, for running the server)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/ycyashchandra/fast-api.git
   cd fast-api




1-  Start the FastAPI server:
   uvicorn main:app --reload
   main is the name of the Python file (e.g., main.py).
app is the FastAPI instance.


2- Open your browser and visit:

API documentation: http://127.0.0.1:8000/docs
ReDoc documentation: http://127.0.0.1:8000/redoc
   
