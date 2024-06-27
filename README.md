# Project Assignment: BookHub Manager

## Objective

Develop a simple web application named BookHub Manager to manage a list of books using the Django framework. The application should support basic CRUD (Create, Read, Update, Delete) operations.

## Project Requirements

- **Programming Language:** Python
- **Web Framework:** Django
- **Database:** SQLite (default database for Django)
- **Front-End:** Basic HTML templates

## Project Tasks

### 1. Project Setup

- Install Django
- Create a new Django project named `bookhub`
- Create a new Django app named `manager`

### 2. Model Creation

- Define a Book model with the following fields:
  - Title (CharField)
  - Author (CharField)
  - Published Date (DateField)

### 3. Database Migrations

- Create and apply database migrations for the Book model

### 4. Forms

- Create a form for the Book model to handle book data input

### 5. Views

- Implement views to handle the following operations:
  - List all books
  - Add a new book
  - Update an existing book
  - Delete a book

### 6. URL Configuration

- Set up URL routing to connect views with appropriate URLs

### 7. Templates

- Create HTML templates for the following views:
  - Book list
  - Book form (for create and update)
  - Book delete confirmation

### 8. Run the Server

- Start the Django development server and test the application
