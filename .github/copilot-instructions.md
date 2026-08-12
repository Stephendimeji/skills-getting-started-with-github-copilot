# Copilot instructions for this repository

## Project overview

This repository contains a small FastAPI application for Mergington High School. It allows students to view extracurricular activities and sign up for them.

## Key files

- `src/app.py`: FastAPI app and in-memory activity data
- `src/static/index.html`: main page markup
- `src/static/app.js`: front-end behavior and API calls
- `src/static/styles.css`: visual styling for activity cards and forms

## Working principles

- Prefer small, intentional changes over broad refactors.
- Keep API and UI behavior consistent when modifying participant logic.
- Do not introduce a database or additional framework unless the task explicitly requires it.
- Validate changes with the smallest relevant command and check whether the behavior is correct in the browser when needed.

## Validation

Run:

```bash
pytest -q
```

before finalizing work in this repo.
