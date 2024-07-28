# FastAPI CRUD Application with SQLite

This is a sample project demonstrating CRUD operations using FastAPI and SQLAlchemy with SQLite.

## Table of Contents

- [FastAPI CRUD Application with SQLite](#fastapi-crud-application-with-sqlite)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Running the Application](#running-the-application)

## Installation

- Clone this repository:

```bash
git clone https://github.com/solnone/FastAPI-SQLite.git
cd FastAPI-SQLite
```

- Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # For Windows use `.venv\Scripts\activate`
```

- Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Configuration

In the `main.py` file, we use SQLite as the database. The database URL is configured as follows:

```python
DATABASE_URL = "sqlite:///./test.db"
```

## Running the Application

Use the following command to run Uvicorn and start the server:

```bash
uvicorn main:app --reload
```
