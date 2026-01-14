# FastAPI Application 🚀

This repository contains a FastAPI backend application configured with a Python virtual environment for clean dependency management.

---

## Prerequisites

Ensure the following are installed on your system:

- Python 3.8 or higher
- pip (Python package manager)

Check versions:

```
python --version
pip --version
```

### Create Virtual Environment

Create a virtual environment named .venv:

python -m venv .venv

### Activate Virtual Environment

- Windows

```
./.venv/scripts/activate
```

- macOS / Linux

```
source .venv/bin/activate
```

Once activated, your terminal will show (.venv).

- Install FastAPI

- Install FastAPI with all standard dependencies:

```
pip install "fastapi[standard]"
```

- Run the FastAPI Application

### Start the FastAPI development server using:

```
python -m fastapi dev main.py
```

### Application URLs:

API: http://127.0.0.1:8000

Swagger UI: http://127.0.0.1:8000/docs

ReDoc UI: http://127.0.0.1:8000/redoc

### Generate Requirements File

Create a requirements.txt file with installed dependencies:

```
pip freeze > requirements.txt
```

### Project Structure

```
├── .venv/
app/
├── middleware/
│   ├── timer.py
│   └── __pycache__/
│       └── timer.cpython-312.pyc
├── routes/
│   ├── issues.py
│   └── __pycache__/
│       └── issues.cpython-312.pyc
├── schemas.py
├── storage.py
└── __pycache__/
    ├── schemas.cpython-312.pyc
    └── storage.cpython-312.pyc
data/
└── issues.json
├── main.py
└── README.md
├── requirements.txt
```

### Tech Stack

Backend Framework: FastAPI
Language: Python
