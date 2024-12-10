📝 Todo-List Application
A simple, intuitive To-Do List Application built with Django. This application allows users to manage their daily tasks efficiently, offering features like adding, updating, and deleting tasks. It also includes an admin panel for task management.
🛠️ Installation Guide
Follow these steps to set up and run the To-Do List Application on your local machine.

Step 1: Set Up a Virtual Environment
 
python -m venv venv
Activate the virtual environment:

Windows:
 
.\venv\Scripts\activate
macOS/Linux:
 
source venv/bin/activate
Step 2: Install Dependencies
Install Django:

 
pip install django
Step 3: Run Migrations
Set up the database by running migrations:

 
python manage.py makemigrations
python manage.py migrate
Step 4: Create a Superuser
Create an admin account to access the admin panel:

 
python manage.py createsuperuser
Provide the username, email, and password when prompted.

Step 5: Run the Development Server
Start the development server to test the application:

 
python manage.py runserver
