# Expense Tracker

A simple and clean expense tracking web application built with Flask and SQLite.  
It allows users to record expenses, filter them by date and category, and visualize spending using charts.

---

## Features

- Add, edit, and delete expenses
- Filter expenses by:
  - Date range
  - Category
- View total spending for the selected filter
- Visualize data with:
  - Category-wise pie chart
  - Spending-over-time bar chart
- Export filtered data as CSV
- Light / Dark theme toggle
- Clean, responsive UI

---

## Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** HTML (Jinja templates), Tailwind CSS
- **Charts:** Chart.js

---

## Project Structure
```
Expense-Tracker/
├── app.py
├── requirements.txt
├── instance/
│   └── expenses.db
├── templates/
│   ├── base.html
│   ├── index.html
│   └── edit.html
└── README.md
```

---

## How to Run Locally

1. **Create a virtual environment**
  ```bash
  python -m venv venv
  ```
2. **Activate the virtual environment**
  - Windows:
  ```bash
  venv\Scripts\activate
  ```
  - macOS / Linux:
  ```bash
  source venv/bin/activate
  ```
3. **Install dependencies**
  ```bash
  pip install -r requirements.txt
  ```

4. **Run the application**
  ```bash
  python app.py
  ```

5. **Open in browser**
  http://127.0.0.1:5000/
  
