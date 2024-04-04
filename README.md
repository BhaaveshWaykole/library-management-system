# IIT-M BS APP DEV - 1 Project
## Library Managament System

### To Create virtual environment
- For linux `python3 -m venv .env`
- For windows `python -m venv .env`

### To activate virtual environment
- For linux `source .env/bin/activate`
- For windows `.\.env\Scripts\activate`

### To run the application
- For linux `python3 app.py`
- For windows `python app.py`



```
library management system
├─ .git
├─ .gitignore
├─ app.py
├─ application
│  ├─ database.py
│  ├─ models.py
│  ├─ routes.py
│  ├─ variables.py
│  ├─ __init__.py
│  └─ __pycache__
│     ├─ database.cpython-311.pyc
│     ├─ models.cpython-311.pyc
│     ├─ routes.cpython-311.pyc
│     └─ __init__.cpython-311.pyc
├─ instance
│  └─ database.sqlite3
├─ README.md
├─ requirements.txt
├─ static
│  ├─ librarian_dashboard.css
│  ├─ login.css
│  └─ register.css
├─ templates
│  ├─ index.html
│  ├─ librarian
│  │  ├─ book
│  │  │  ├─ add.html
│  │  │  ├─ delete.html
│  │  │  └─ edit.html
│  │  ├─ dashboard.html
│  │  └─ section
│  │     ├─ add_section.html
│  │     ├─ books.html
│  │     └─ sections.html
│  ├─ login.html
│  ├─ register.html
│  ├─ user_account_settings.html
│  ├─ user_browse_sections.html
│  ├─ user_dashboard.html
│  └─ user_my_books.html
└─ __pycache__
   └─ app.cpython-311.pyc

```