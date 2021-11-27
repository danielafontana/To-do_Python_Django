## To-do_Python_Django

==================================================

#### Objective:
	
	This project aimed to create a user-friendly interface for a to-do list using Python and Django.

==================================================
	
	Getting Started
---------------

To work on the sample code, you'll need to clone your project's repository to your
local computer.

1. If you want, create a Python virtual environment for your Django project. This virtual
   environment allows you to isolate this project and install any packages you
   need without affecting the system Python installation. At the terminal, type
   the command:

        $ python -m venv ./venv

2. Activate the virtual environment:

        $ venv\Scripts\activate.bat

3. Migrate, to propagate the changes you make to your models (adding a field, deleting a model, etc.) into your database.

        $ python manage.py migrate


What Do I Do Next?
------------------

1. First we’ll need to create a user who can login to the admin site. Run the command:

		$ python manage.py createsuperuser

2. Enter your desired username and press enter.

3. You will then be prompted for your desired email address.

4. The final step is to enter your password. You will be asked to enter your password twice, the second time as a confirmation of the first.

		Password: **********
		Password (again): *********
		Superuser created successfully.


And finally, we start the development server!
------------------

1. Start the Django development server:

        $ python manage.py runserver

2. Open localhost:8000 in a web browser to view your application.

Obs.: Use your Superuser and Password to login.


## Enjoy the apllication!!!	