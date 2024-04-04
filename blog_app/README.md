### Steps to start this project

1. Clone the monorepo
2. Go to blog_app by running the command -
   `cd blog_app/`
3. Create a virtual environment by running the command -
   `python3 -m venv venv`
4. Activate the virtual environment by running the command (any one)-
   `source venv/bin/activate` (on mac/linux)
   `venv\Scripts\activate` (on windows)
5. Install the dependencies by running the command -
   `pip install -r requirements.txt`
   `pip install -r requirements_dev.txt`
6. Create migrations by running the command -
   `python manage.py migrate`
7. Create superuser by running the command -
   `python manage.py createsuperuser`
   Note:- Follow along with the instructions to give username, email & password for
   creating superuser
8. Post succesfully creating superuser start the project by running the command -
   `python manage.py runserver`
9. Go to `localhost:8000` to check out the project and login with the superuser creds
