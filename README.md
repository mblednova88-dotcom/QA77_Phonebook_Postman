# Phonebook API Testing Project

API testing project for Phonebook web application using Postman collections and GitHub Actions.

## Tech Stack
- Postman
- REST API
- GitHub Actions
- JSON

## Features
- API request testing
- CRUD operations testing
- Automated API collection runs
- Environment variables
- Response validation
- Status code verification

## Project Structure
- `Postman Collections/` — API collections and requests
- `.github/workflows/` — GitHub Actions CI configuration

## Automated Testing
This project uses GitHub Actions to automatically run Postman collections.

## Test Coverage
- User registration
- User login
- Contact creation
- Contact update
- Contact deletion
- Response validation

## Technologies Used
- Postman
- Newman
- GitHub Actions

## How to Run Tests

### Run locally with Newman

```bash
newman run collection.json
```

### Run in GitHub Actions
Tests run automatically via CI workflow.

## Author
Marina Blednova
Junior QA Engineer
