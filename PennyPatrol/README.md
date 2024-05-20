# Penny Patrol Expense Tracker

Penny Patrol is a web application built with Django, Python, MySQL, HTML, CSS, and Bootstrap. It allows users to track and manage their expenses efficiently.

## Features

- User registration and authentication system
- Add, edit, and delete expenses
- Categorize expenses by category
- Filter expenses by date, category, or amount
- Generate reports and visualizations of expenses
- Export expense data in CSV format

## Installation

1. Clone the repository:

 - git clone https://github.com/mohammedatif10/PennyPatrol/tree/main/PennyPatrol
 
 
2. Install the required dependencies:

- use pip install django
and any other dependencies that are required.


3. Set up the MySQL database:
   - Create a new MySQL database for the project.
   - Update the database settings in `expense_tracker/settings.py` file with your database credentials.

4. Apply database migrations:

- python manage.py migrate


5. Start the development server:

- python manage.py runserver


6. Access the application in your web browser at `http://localhost:8000`.

## Usage

- Register a new user account or log in with an existing account.
- Add your expenses by providing details such as date, category, amount, and description.
- Use the provided options to filter and manage your expenses.
- Generate reports and visualizations to gain insights into your spending habits.
- Export your expense data in CSV format for further analysis.

### Requirements

- [Django](https://www.djangoproject.com/)
- [MySQL](https://www.mysql.com/)




