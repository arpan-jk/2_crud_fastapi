# Backend - FastAPI Project

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
uvicorn app.main:app --reload
```

## steps
1. created basic fastapi backend and installed neccesary dependencies.
```bash
   pip install fastapi==0.116.0 uvicorn==0.35.0 sqlalchemy==2.0.41 psycopg2-binary==2.9.10
```
2. created a local pg database `assignment-crud`.
```bash
sudo apt install postgresql postgresql-contrib
sudo service postgresql start
sudo -u postgres psql
CREATE DATABASE ASSIGNMENT_CRUD;
\q
```
3. connected it to `DBeaver`.
4. created blogs and users table.
```sql




```


## References
1. [fastapi docs](https://fastapi.tiangolo.com/#installation)
2. [uvicorn docs](https://www.uvicorn.org/#config-and-server-instances)
3. [fastapi router](https://fastapi.tiangolo.com/reference/apirouter/)
4. https://mattermost.com/blog/building-a-crud-fastapi-app-with-sqlalchemy/
5. 