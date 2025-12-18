# Expense Tracker Project

This README explains how to set up and run the **Expense Tracker** project on your local machine.

---

## 1. Prerequisites

- Python 3.10 or higher
- Git (optional, for version control)
- VS Code (recommended)
- Basic knowledge of Django

---

## 2. Download the Project

 **Clone from GitHub:**
```bash
git clone https://github.com/vishwa-cell/expense-tracker.git




##3. Create Virtual Environment
Create a virtual environment to isolate dependencies. You can use any name (here, fin_venv is used).

Windows
bash

python -m venv fin_venv
fin_venv\Scripts\activate


##4. Install Dependencies
Install all required packages using requirements.txt:

bash

pip install --upgrade pip
pip install -r requirements.txt

This will install:

Django
NumPy, Pandas, Plotly
All other dependencies

##5. Apply Migrations
Run Django migrations to set up the database:

bash

python manage.py migrate

##6. Create Superuser (Optional)
To access the admin panel:

bash

python manage.py createsuperuser


##7. Run the Development Server
Start the Django development server:

bash

python manage.py runserver


