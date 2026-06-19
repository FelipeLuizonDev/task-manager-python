# Task Manager API

[![Python](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/) [![Flask](https://img.shields.io/badge/Flask-2.3-black.svg)](https://flask.palletsprojects.com/)

A simple REST API for task management built with **Python** and **Flask** as part of my backend learning journey.

The project implements a complete **CRUD (Create, Read, Update and Delete)** for tasks and includes automated tests using **Pytest** and **Requests**.

## Technologies

* Python 3
* Flask
* Pytest
* Requests
* Git
* GitHub

---

## Features

* Create a new task
* List all tasks
* Retrieve a task by ID
* Update an existing task
* Delete a task
* Automated API tests

---

## Project Structure

```plaintext
task-manager-python/
├── models/
│   └── task.py
├── .gitignore
├── README.md
├── requirements.txt
├── app.py
└── tests.py
```

---

## Running the Project

### Prerequisites

* Python 3
* pip

### Clone the repository

```bash
git clone https://github.com/FelipeLuizonDev/task-manager-python.git
```

### Navigate to the project folder

```bash
cd task-manager-api-python
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Start the application

```bash
python app.py
```

The server will be available at:

```
http://127.0.0.1:5000
```

---

## Running the Tests

With the API running, execute:

```bash
pytest tests.py
```

---

## API Endpoints

### Create task

```http
POST /tasks
```

Example body:

```json
{
  "title": "Study Flask",
  "description": "Complete CRUD project"
}
```

---

### List all tasks

```http
GET /tasks
```

---

### Get task by ID

```http
GET /tasks/{id}
```

---

### Update task

```http
PUT /tasks/{id}
```

Example body:

```json
{
  "title": "Updated title",
  "description": "Updated description",
  "completed": true
}
```

---

### Delete task

```http
DELETE /tasks/{id}
```

---

## Author

**Felipe Luizon**

* GitHub: https://github.com/FelipeLuizonDev
* LinkedIn: https://www.linkedin.com/in/felipeluizon
