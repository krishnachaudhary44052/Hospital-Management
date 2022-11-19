# Django-based-Hospital-Mangament-System



This is a Django based Hospital Management System. The main objective of this project is, the patient can make an appointment with the doctor of particular organization through online

## Requirements
For this project to run on your system we need the some packages to be installed for that open your command prompt and navigate to the folder where there is requirements.txt file and enter the command "pip install -r requirements.txt"

## Run this project


To run this project, open the command prompt in your project folder

Note:
1.You have to navigate to the folder where there is manage.py file.
# in case this commands not work delete mydb.json and follow all step again
2.python manage.py dumpdata > mydb.json
3.create database in mysql with name ""
3.python manage.py migrate
4.python manage.py loaddata mydb.json
5.python manage.py createsuperuser  
6.python manage.py runserver   





Enter the command: python manage.py runserver.
You will get a link with the ip address of localhost with some port number. Copy the link and paste it in the browser.

