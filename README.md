
# Django-Social-Media-WebApp

A simple Twitter like Social Media Web Application

---

# Features

- User Authentication and Registration
- Adding new posts
- Editing posts Asyncrhonously
- Liking and unliking posts Asyncrhonously
- Following Users
- User Profile Page

---

# Live Demo
> Click The Picture :)
[![Live Demo](https://lh5.googleusercontent.com/jCiDvj3nV1c2ef199zyNdvdTKb6A-vY1ksFiDNaVyYou4vAes4_GPgQN16_uUw0jRr6Jy_Q5Tntk_9r8RO5N=w1920-h919)](https://snapperr.herokuapp.com/)

---

# Setting it up
> Install requirements via pip: `pip install -Ur requirements.txt`
1. First Navigate to the [settings.py](project4/settings.py) file in project4 folder
2. Comment line 35  ` 'django.contrib.admin',`
3. Navigate to the [urls.py](project4/urls.py) file in project4 folder
4. Comment line 24  ` path("admin/", admin.site.urls),`
5. run these in order 

    ```bash
    python manage.py makemigrations network
    python manage.py migrate --run-syncdb
    python manage.py migrate
    ```
6. Then uncomment the first 2 lines
7. run `python manage.py createsuperuser`
8. Create your admin user
9. run `python manage.py runserver`
