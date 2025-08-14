# Request Methods

- GET

localhost:8000/api/companies/

- POST

localhost:8000/api/companies/

{
    "name": "Google",
    "website": "https://www.google.com",
    "foundation": 1997
}

{
    "name": "Facebook",
    "website": "https://www.facebook.com",
    "foundation": 2004
}    

{
    "name": "OpenAI",
    "website": "https://www.openai.com",
    "foundation": 2015
}

- PUT

localhost:8000/api/companies/1

{
    "name": "Google",
    "website": "https://www.google.com",
    "foundation": 1998
}

- DELETE

localhost:8000/api/companies/1

---

pip install -r requirements.txt

docker compose -f compose.yaml up -d db

docker compose -f compose.yaml up -d app

docker compose -f compose.yaml down -v

docker compose -f compose.dev.yaml up --build