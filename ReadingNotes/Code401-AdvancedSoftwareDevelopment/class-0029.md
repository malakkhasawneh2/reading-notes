# ***Django Custom User***

Django ships with a built-in User model for authentication and if you'd like a basic tutorial on how to implement log in, log out, sign up and so on see the Django Login and Logout tutorial for more.

However, for a real-world project, the official Django documentation highly recommends using a custom user model instead. This provides far more flexibility down the line so, as a general rule, always use a custom user model for all new Django projects.

## Setup

To start, create a new Django project from the command line. We need to do several things:

* create and navigate into a dedicated directory called accounts for our code
* install Django
* make a new Django project called config
* make a new app accounts
* start the local web server

```
$ cd ~/Desktop
$ mkdir accounts && cd accounts
$ pipenv install django~=3.1.0
$ pipenv shell
(accounts) $ django-admin.py startproject config .
(accounts) $ python manage.py startapp accounts
(accounts) $ python manage.py runserver
```

## Custom User Model

Creating our initial custom user model requires four steps:

* update config/settings.py
* create a new CustomUser model
* create new UserCreation and UserChangeForm
* update the admin

In settings.py we'll add the accounts app and use the AUTH_USER_MODEL config to tell Django to use our new custom user model in place of the built-in User model. We'll call our custom user model CustomUser.

## Superuser

It's helpful to create a superuser that we can use to log in to the admin and test out log in/log out. On the command line type the following command and go through the prompts.

```
 python manage.py createsuperuser
```

# Django x


![dd](https://github.com/wsvincent/djangox/raw/master/homepage.png)
## Installation

DjangoX can be installed via Pip, Pipenv, or Docker depending upon your setup. To start, clone the repo to your local computer and change into the proper directory.

for poetry user :
poetry init -n
poetry shell
then add the dependence using poetry add 

## Setup

### Run Migrations

(djangox) $ python manage.py migrate

### Create a Superuser

(djangox) $ python manage.py createsuperuser

### Confirm everything is working

(djangox) $ python manage.py runserver

### Load the site at <http://127.0.0.1:8000>
