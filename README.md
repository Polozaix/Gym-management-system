# Gym Management System — Flask Prototype

A small Flask starter project for experimenting with a gym-management web application.

> **Current status:** Early prototype. The code currently serves one homepage at `/` that displays “Hello, Gym Management System!”. It does **not** yet implement membership accounts, bookings, payments, or database-backed gym management.

## Run locally

**Requirements:** Python 3 and pip.

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS / Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python app.py
```

Visit <http://127.0.0.1:5000/> to see the homepage.

`app.py` runs Flask in debug mode, so **use it only for local development**, not as a production deployment.

## Project contents

- `app.py` — Flask application with a single home route
- `requirements.txt` — Python packages used for local development
- `.gitignore` — local files and environments excluded from version control

## Next steps

- [ ] Decide on the membership and customer data model
- [ ] Add persistent data storage and CRUD routes
- [ ] Build simple forms and templates
- [ ] Add validation, tests and error handling
- [ ] Replace debug mode with a production-ready configuration before deployment

This Flask experiment is separate from my **C#/.NET Windows Forms gym customer management** university project. Their features should not be treated as interchangeable.
