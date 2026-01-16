# Dokai Backend API

FastAPI backend application for the Dokai project.

## Prerequisites

- Python 3.9 or higher
- Poetry (install from https://python-poetry.org/docs/#installation)

## Setup

1. Install dependencies:
```bash
poetry install
```

2. Activate the Poetry shell:
```bash
poetry shell
```

Or run commands with `poetry run`:
```bash
poetry run uvicorn main:app --reload
```

## Running the Server

```bash
poetry run uvicorn main:app --reload
```

Or if you're in the Poetry shell:
```bash
uvicorn main:app --reload
```

The API will be available at `http://localhost:8000`

## API Documentation

Once the server is running, you can access:
- Interactive API docs: `http://localhost:8000/docs`
- Alternative docs: `http://localhost:8000/redoc`

