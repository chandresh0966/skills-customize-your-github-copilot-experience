# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build modern, efficient REST APIs using the FastAPI framework. By completing this assignment, you'll understand HTTP methods, request/response handling, data validation, and best practices for creating scalable web services that can be consumed by client applications.

## 📝 Tasks

### 🛠️ Create Basic API Endpoints

#### Description
Set up a FastAPI application with basic CRUD (Create, Read, Update, Delete) endpoints for a simple resource (e.g., a task, product, or note).

#### Requirements
Completed program should:

- Initialize a FastAPI application with proper imports and app instance
- Create a GET endpoint to retrieve all items
- Create a GET endpoint to retrieve a single item by ID
- Implement request validation using Pydantic models
- Return appropriate HTTP status codes for each operation (200, 201, 404, etc.)

### 🛠️ Implement Request and Response Validation

#### Description
Add data validation to ensure API requests contain valid data and responses are properly structured.

#### Requirements
Completed program should:

- Define Pydantic models for request/response data
- Use type hints for function parameters and return values
- Validate incoming JSON data automatically
- Return appropriate error responses with meaningful messages when validation fails
- Document request/response schemas with class attributes

### 🛠️ Create POST and DELETE Endpoints

#### Description
Implement endpoints to add new items to your resource and remove existing items.

#### Requirements
Completed program should:

- Create a POST endpoint that accepts JSON data and adds a new item
- Create a DELETE endpoint to remove items by ID
- Handle duplicate entries or invalid deletions with appropriate error responses
- Store items in a data structure (list, dictionary, or in-memory database)
- Test endpoints using FastAPI's interactive documentation (Swagger UI or ReDoc)
