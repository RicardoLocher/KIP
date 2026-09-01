# What this is
A simple chat room which I want to develop into a private Social Media for family and friends.

## Prerequisities
- Python
- pip

## How to run:
- Create virtual environment:
`python -m venv myenv`

- Activate it:
`source myenv/bin/activate`

- Install requirements:
`pip install -r requirements.txt`

- Make Django migrations:
    - `python manage.py makemigrations`
    - `python manage.py migrate`

- Run the Server:
`python manage.py runserver`