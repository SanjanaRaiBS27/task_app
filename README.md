Task Smash 2.0
Task Smash 2.0 is a simple task management web application built with Flask and SCSS, allowing users to add, edit, and delete tasks easily.

Features
✅ Add, edit, and delete tasks
✅ Responsive UI with SCSS styling
✅ Simple Flask backend

Tech Stack
Frontend: HTML, SCSS, JavaScript
Backend: Flask (Python)
Database: SQLite / MySQL (if applicable)


Folder Structure
my_flask_app/
|-- env/                  # Virtual environment (not pushed to GitHub)
|-- instance/
|   |-- databases.db      # SQLite database file
|-- static/
|   |-- styles.css        # Compiled CSS file
|   |-- styles.css.map    # CSS map file
|   |-- styles.scss       # SCSS source file
|-- templates/
|   |-- base.html         # Base template
|   |-- edit.html         # Edit task template
|   |-- index.html        # Home page template
|-- app.py                # Main Flask application
|-- testing.html          # Testing file (if applicable)
|-- README.md             # Project documentation
|-- requirements.txt      # Python dependencies



Setup Instructions

1. Clone the Repository

git clone https://github.com/SanjanaRaiBS27/task_app.git
cd task_app

2. Create a Virtual Environment

python -m venv env
source env/bin/activate  # On macOS/Linux
env\Scripts\activate     # On Windows

3. Install Dependencies

pip install -r requirements.txt

4. Run the Flask Application

python app.py

The application should now be running on http://127.0.0.1:5000/.



Git Commands Used

Initialize Git repository:

git init

Add all files to Git:

git add .

Commit changes:

git commit -m "first commit"

Rename branch to main:

git branch -M main

Add remote repository:

git remote add origin https://github.com/SanjanaRaiBS27/task_app.git

Push code to GitHub:

git push -u origin main

Features

Add, Edit, and Delete Tasks

Simple UI with HTML, CSS (SCSS for styling)

Uses SQLite for database storage

Flask backend with Jinja templating

Future Improvements

User authentication

Task categories and priorities

API for external integrations