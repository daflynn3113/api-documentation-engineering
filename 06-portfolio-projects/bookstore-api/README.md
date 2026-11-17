# Bookstore REST API

## 1. Project Overview

The Bookstore REST API is a sample RESTful web service documentation project designed to demonstrate practical API documentation engineering skills.

The API represents a bookstore system that allows clients to retrieve, create, update, and delete book records.

This project is part of my API Documentation Engineering portfolio. It demonstrates the use of Markdown, JSON, YAML, OpenAPI, and Git-based documentation workflows.

## 2. Project Objectives

- Understand REST API architecture and HTTP methods.
- Define API resources and endpoint behavior.
- Create JSON request and response examples.
- Develop an OpenAPI 3.1 specification.
- Document authentication and error-handling behavior.
- Produce clear, developer-friendly API documentation.
- Validate consistency between API specifications and documentation.

## 3. API Operations

| Resource | HTTP Method | Operation                |
| -------- | ----------- | ------------------------ |
| Books    | GET         | Retrieve all books       |
| Books    | GET         | Retrieve a specific book |
| Books    | POST        | Create a new book        |
| Books    | PUT         | Update an existing book  |
| Books    | DELETE      | Delete a book            |

## 4. Book Resource Model

Each book will contain the following properties:

| Property        | Data Type | Description                        |
| --------------- | --------- | ---------------------------------- |
| id              | Integer   | Unique book identifier             |
| title           | String    | Title of the book                  |
| author          | String    | Author's name                      |
| isbn            | String    | International Standard Book Number |
| publicationYear | Integer   | Year of publication                |
| price           | Number    | Book price                         |
| available       | Boolean   | Availability status                |

## 5. Technology and Tools

- REST and HTTP
- JSON and YAML
- OpenAPI Specification 3.1
- Visual Studio Code
- Git and GitHub
- Postman

## 6. Project Structure

| Directory/File | Purpose                            |
| -------------- | ---------------------------------- |
| `openapi/`     | API specification                  |
| `examples/`    | JSON request and response examples |
| `docs/`        | Developer documentation            |
| `README.md`    | Project overview                   |

## 7. Documentation Deliverables

1. API overview and getting-started guide.
2. Endpoint reference.
3. OpenAPI specification.
4. JSON examples.
5. Error response documentation.

## 8. Project Status

**Status:** Documentation development in progress.

This project initially defines an API contract and its supporting documentation. It does not represent a deployed or operational backend service.

## 9. Author

David Flynn

GitHub: https://github.com/daflynn3113
