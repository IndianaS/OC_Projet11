# - P11 DA Python OpenClassrooms .

# - Améliorations du projet 8 Pur Beurre . 

# - Description:
- Improve an existing project in Python

# - Added features :
- 1: An auto-completion system .
- 2: User password reset option .
- 3: The option to delete favorites .

# - 1: Initialization of the project locally:
- 1: To initialize the virtual environment: `pipenv install`.
- 2: To position yourself in pipenv : `pipenv shell`.

# - 2: Launch the project locally:
- : If you have already initialized the virtual environment.
- 1: Execute the command `python manage.py installdb` to create the database, then insert the data.
- 2: To run the app: `python manage.py runserver`.
- 3: Once launched, go to your browser and enter the following url: "http://127.0.0.1:8000/".

# -3: Unit test:
- : To launch the unit tests execute in the terminal the command `coverage run --source='.' manage.py test`.
- : To view the test report: `coverage report`.
