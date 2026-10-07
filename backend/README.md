# Deemo backend

This folder contains the Python FastAPI service for Deemo.

## Run locally

From this folder, create and activate a virtual environment, then install the
dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Start the development server:

```powershell
uvicorn app.main:app --reload
```

The API is available at `http://127.0.0.1:8000`, with interactive
documentation at `/docs`. The health endpoint is `/health`.
