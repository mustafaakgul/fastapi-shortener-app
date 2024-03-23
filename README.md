### Building a lightning-fast URL shortener with Python and FastAPI

##### Terminal Commands:
* uvicorn shortener_app.main:app --reload

##### Python Console:
* from shortener_app.database import SessionLocal
* db = SessionLocal()
* from shortener_app.models import URL 
* db.query(URL).all()
* from shortener_app.keygen import create_random_key
* create_random_key()
* create_random_key(length=8)

##### URLS: 
* http://127.0.0.1:8000/
* http://127.0.0.1:8000/docs : Auto-generated documentation
* http://127.0.0.1:8000/redoc : Auto-generated documentation