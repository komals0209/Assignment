

## Requirements
- Python 3.11+
- PostgreSQL installed and running
- Run: pip install -r requirements.txt

## DB Setup
Create PostgreSQL DB:
CREATE DATABASE vibeosys_product;

Update `DATABASE_Config` in `app/database.py` 

## Run the app
uvicorn main:app --reload

APIs available:
- GET /product/list?page=1
- GET /product/{id}/info
- POST /product/add
- PUT /product/{id}/update

