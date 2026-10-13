# Python + SQL with SQLite

A self-contained Python script that uses the built-in `sqlite3` module to create a small student/course database and run a full range of SQL operations against it.

**Tech:** Python · SQLite (`sqlite3`, no external dependencies)

## What it covers

- **Schema creation:** `Students` and `Courses` tables with primary keys and constraints
- **Inserting data** with parameterized queries
- **Querying:** `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`
- **Modifying data:** `UPDATE`, `DELETE`, `INSERT`
- **Aggregation:** `COUNT`, `AVG`, `MAX`/`MIN`, `GROUP BY`

## ▶️ Run it

```bash
cd PythonSQLExamples
python main.py
```

The script creates a fresh `students.db` on each run and prints the result of every query.
