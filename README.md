# wisdompets

My first Django Project.

To run server: python3 manage.py runserver

Steps:
1. pip3 install django==1.11.7
2. django-admin.py startproject wisdompets
3. python3 manage.py startapp adoptions
4. add 'adoptions' in INSTALLED_APPS in wisdompets/settings.py
5. define model in models.py
6. python3 manage.py makemigrations
7. python3 manage.py showmigrations
8. python3 manage.py migrate
9. add load_pet_data.py to load csv file
10. python3 manage.py load_pet_data
11. Update admin.py
12. python3 mange.py createsuperuser
13. go to localhost:8000/admin/
14. Update urls.py
15. Update views.py
16. Add templates
17. Integrate CSS and JavaScript
