# Object-Relations-CodeChallenge

This project models the relationships between **Authors**, **Articles**, and **Magazines** using **SQLite** and **raw SQL queries** in Python.

## 📁 Features
- Authors can write many articles.
- Magazines can publish many articles.
- Articles belong to both an author and a magazine.
- Built with raw SQL (no ORM).
- Includes tests, database setup, and sample data.

## 🧪 How to Run

1. Set up the database:
   python run_setup.py

2. Run tests:
   pytest

3. Debug or test functionality:
   python lib/debug.py

## ✨ Technologies Used
- Python
- SQLite
- pytest (for testing)