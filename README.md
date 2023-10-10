# react-backend-django

1. Do the necessary stuffs and come here after you get some hold of `react-master-class` ![Click here](https://github.com/astrodestroyergithub/react-master-class)
2. In terminal do this:
`pip install django-rest-framework`\
3. Execute the following commands:
`pip`
`pip freeze`
`pip freeze > requirements.txt`
`pip install -r requirements.txt`

4. Creating REST API Backend:
(i) Create a Model (representation of data in Django App)
(ii) Create a url path (location to access the data)
(iii) Create a Serializer (describes how we go from db objects to json data)

5. Execute:
`python manage.py runserver`
Ctrl+C
`python manage.py migrate`

6. Make the necessary url paths inside `urls.py`
Create a file `models.py` inside `customers` folder`

7. Goto `settings.py` and add the name of the app you are working on

8. Execute the command in terminal:
`python manage.py makemigrations customers`
`python manage.py migrate`

9. Inside `customers` folder, create 2 files: `views.py` and `serializers.py`

10. Make changes in `settings.py`

11. Create file `admin.py` inside `customers` folder

12. `python manage.py createsuperuser`
Set the username, password, etc.
`python manage.py runserver`

13. `pip install django-cors-headers`
`pip freeze > requirements.txt`

14. Make changes in `INSTALLED_APPS` and `MIDDLEWARE`