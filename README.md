▶️ # FastAPI Learning

A collection of hands-on examples and practice projects created while learning **FastAPI**. This repository documents my journey of exploring modern backend development by building REST APIs with Python.

## About

FastAPI is a modern, high-performance web framework for building APIs with Python. It offers automatic data validation, interactive API documentation, and excellent developer productivity.

This repository will be updated regularly as I continue learning new concepts and building practical applications.

## Tech Stack

* Python
* FastAPI
* Uvicorn

## Repository Structure

```text
.
├── main.py
├── requirements.txt
├── .gitignore
├── README.md
└── LICENSE
```

## Topics Covered

### Fundamentals

* Installation & Setup
* Creating the First API
* Running the Development Server
* GET Requests

### Request Methods

* GET
* POST
* PUT
* PATCH
* DELETE

### Request Handling

* Path Parameters
* Query Parameters
* Request Body
* Form Data
* File Uploads
* Request Validation

### Data Modeling

* Pydantic Models
* Nested Models
* Response Models
* Field Validation

### Routing

* APIRouter
* Tags
* Modular Project Structure

### Error Handling

* HTTP Exceptions
* Status Codes
* Custom Exception Handlers

### Dependency Injection

* Dependencies
* Security Dependencies

### Database Integration

* SQLite
* SQLAlchemy
* PostgreSQL
* CRUD Operations
* Alembic Migrations

### Authentication & Security

* OAuth2
* JWT Authentication
* Password Hashing
* Protected Routes

### Advanced Features

* Middleware
* CORS
* Background Tasks
* Environment Variables
* Logging
* Configuration Management

### Testing

* TestClient
* Pytest
* API Testing

### Deployment

* Docker
* Gunicorn
* Nginx
* Render
* Railway
* AWS

## Running the Project

Clone the repository:

```bash
git clone https://github.com/<your-username>/fastapi-hello-api.git
cd fastapi-hello-api
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the development server:

```bash
uvicorn main:app --reload
```

Open the application:

* **Home:** http://127.0.0.1:8000
* **Swagger UI:** http://127.0.0.1:8000/docs
* **ReDoc:** http://127.0.0.1:8000/redoc

## Learning Goal

The objective of this repository is to build a strong foundation in FastAPI and gradually develop production-ready backend applications using modern Python development practices.

