# # Backend - FastAPI Project

This is the backend of the project, built using FastAPI.

## Setup

1. Create and navigate to the backend folder:

```bash
mkdir backend
cd backend
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate
```
3. Install neccessary dependencies
```bash
pip install -r requirements.txt
```
4. Start the server
```bash
uvicorn main:app --reload
```