# Flask Expense Tracker

A simple and functional expense tracker web application built with Flask and SQLite. Helps users manage personal expenses by allowing them to add, store, and view expense records through a clean web interface and RESTful APIs.

---

## Problem Statement

Personal expense tracking requires a lightweight, self-hosted solution with persistent storage and API access for integration.

## Objectives

- Provide a web interface for adding and viewing expenses
- Persist data in SQLite
- Expose REST API endpoints (GET and POST)
- Keep the application simple and dependency-light

## Key Features

- **Add Expenses** — date, category, description, and amount
- **View All Expenses** — display stored records
- **REST API** — JSON-based POST (add) and GET (fetch) endpoints
- **SQLite Persistence** — auto-created database file
- **Jinja2 Templates** — HTML form for user input

## Technologies Used

| Component | Technology |
|-----------|-----------|
| Backend | Python (Flask) |
| Database | SQLite |
| Frontend | HTML (Jinja2 templating) |
| API | JSON REST |

## Project Structure

```
flask-expense-tracker/
├── app.py              # Main Flask application
├── expenses.db         # SQLite database (auto-created)
├── templates/
│   └── index.html      # HTML form for user input
├── static/             # Optional CSS, images, JS
└── README.md
```

## Installation and Setup

### Prerequisites
- Python 3.8+
- pip

### Setup
```bash
pip install flask
python app.py
```

Application runs at `http://localhost:5000`.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | / | View all expenses |
| POST | /add | Add a new expense (JSON) |

## Limitations

- No user authentication
- No expense editing or deletion
- Single-user (no multi-tenant support)

## Author and Contact Information

**SAMALA RAKSHITH BABU**

- Email: samalarakshithbabu7@gmail.com
- LinkedIn: https://www.linkedin.com/in/samala-rakshith-babu-9374ab281/
- GitHub: https://github.com/samalarakshithbabu

## License

No LICENSE file present in repository.