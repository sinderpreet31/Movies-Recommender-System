About this file
create
A Procfile is a file used in Heroku deployments to specify the commands that are executed by the app on startup. Below is an example of a Procfile and a description of its contents:

CODE - web: sh setup.sh && streamlit run app.py

Description: web: Indicates that this process type is for handling web traffic.

gunicorn: Stands for Green Unicorn, a popular HTTP server for Python applications.

your_app_module:app: Specifies the Python module and the WSGI application object that Gunicorn should run. Replace your_app_module with the actual name of your application module, and app with the name of the WSGI application object.

This Procfile is essential for deploying a Python web application on Heroku. It tells Heroku how to run your application using Gunicorn as the HTTP server. Ensure that you have Gunicorn included in your requirements.txt or Pipfile if you're using Pipenv.

CODE : sh setup.sh && streamlit run app.py
