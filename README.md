# Tracker

A REST API for tracking and managing personal expenses and financial records.

## Features

- Full CRUD operations for expense tracking
- Categorize expenses by type
- Filter and sort expense records
- Track spending patterns
- Clean architecture (Entity, Repository, Service, Controller)
- RESTful API design

## Tech Stack

Java | Spring Boot | REST API | HashMap (in-memory storage)

## Getting Started

```bash
git clone https://github.com/JohnImorin/Tracker.git
cd Tracker
```

Run:
```bash
mvn spring-boot:run
```

API runs on `http://localhost:8080`

## API Endpoints

- `GET /api/expenses` - Get all expenses
- `GET /api/expenses/{id}` - Get expense by ID
- `POST /api/expenses` - Create new expense
- `PUT /api/expenses/{id}` - Update expense
- `DELETE /api/expenses/{id}` - Delete expense
- `GET /api/expenses/category/{category}` - Filter by category
- `GET /api/expenses/total` - Get total spending

## Author

John Fabrice Imorin | CS Graduate | Junior Backend Developer  
📧 johnsteiner900@gmail.com | 🔗 [LinkedIn](https://linkedin.com/in/john-fabrice-imorin-526a4722b)
