# git-analyzer-api

A modern, type-safe FastAPI boilerplate with linting, formatting, type checking, testing, Docker support, and pre-commit hooks.

---

## 🚀 Quick Start

### 1. Create and Activate Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies

```bash
pip install -r requirements/base.txt
# Or, for development:
pip install -r requirements/dev.txt
```

---

## 🏃‍♂️ Running the Application Locally

```bash
uvicorn app.main:app --reload
```

---

## 🧪 Running Tests

```bash
pytest
```

---

## 🛠️ Code Quality Checks

Run all checks manually:

```bash
black .
ruff .
mypy .
pytest
```

---

## 🐳 Docker

### Build the Docker image

```bash
docker build -f docker/Dockerfile -t fastapi-app .
```

### Run the Docker container

```bash
docker run -p 8000:8000 fastapi-app
```

---

## 🧹 Pre-commit Hooks

Pre-commit hooks are configured to run formatting, linting, type checking, and tests before each commit.

To install pre-commit hooks:

```bash
pre-commit install
```

---