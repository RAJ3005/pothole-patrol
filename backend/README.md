# Pothole Patrol

Pothole Patrol is a FastAPI-based backend that provides APIs for road maintenance and reporting potholes efficiently.

## 🚀 Features
- FastAPI-powered REST API
- Integration with a React frontend (Vite + TypeScript)
- Automated testing with pytest
- Linting & formatting with Ruff and pre-commit hooks

## 🛠 Installation

### Clone the repository
```
git clone git@github.com:your-username/pothole-patrol.git
cd pothole-patrol
````

### Set up the backend
```
cd backend
poetry install
poetry run uvicorn main:app --reload
```