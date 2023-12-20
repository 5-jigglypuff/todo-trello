# todo-trello backend

## Getting started

Create a virtual environment
```
$ python -m venv .venv
$ source .venv/bin/activate
```

Install dependencies
```
(.venv)$ pip install -r requirements.txt
```

Run the server
```
(.venv)$ uvicorn main:app --reload
```

## Endpoints

```
GET http://127.0.0.1:8000/

GET http://127.0.0.1:8000/tasks/65823d1b265a47cb2df90fdc

GET http://127.0.0.1:8000/task/658272ea694cf9ea7b926103

POST http://127.0.0.1:8000/task/65823d1b265a47cb2df90fdc?name=task_name&desc=task_description

PUT http://127.0.0.1:8000/task/658272ea694cf9ea7b926103?name=task_name_1&desc=task_description_1

DELETE http://127.0.0.1:8000/task/658272ea694cf9ea7b926103
```
