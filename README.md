# Flask Todo App

A simple **Todo App** built with Flask and SQLite. This application allows users to create, update, and delete tasks. It's a great example of how to build and deploy a Flask app.

---

## Features
- Add new tasks with a description.
- Update existing tasks.
- Delete tasks.
- Automatically sorts tasks by creation date.

---

## Prerequisites
Make sure you have the following installed:
- [Python 3.9+](https://www.python.org/)
- [Pip (Python Package Installer)](https://pip.pypa.io/en/stable/)

---

## Project Structure
```
 ├── server.py  # Main Flask application 
 ├── templates/ # HTML templates 
 │ ├── index.html # Main page for tasks 
 │ ├── update.html # Update task page 
 ├── requirements.txt # Python dependencies 
 ├── vercel.json # Configuration for Vercel deployment
```
 
---

## Installation

### 1. Clone the Repository

### 2. Create a Virtual Environment
- ``` python -m venv venv ```
- ```source venv/bin/activate    # On macOS/Linux```
- ```venv\Scripts\activate       # On Windows```

### 3. Install Dependencies
- ```pip install -r requirements.txt```

### 4. Set Up the Database
- ```from server import db```
- ``` db.create_all()```

### 5. Run the Flask Application Locally
- ```python server.py```



