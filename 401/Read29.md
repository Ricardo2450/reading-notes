# Django Custom User

> ## [Django Custum User Model](https://learndjango.com/tutorials/django-custom-user-model)

* There are two modern ways to create a custom user model in Django: AbstractUser and AbstractBaseUser.
  * AbstractBaseUser requires much, much more work.

* Creating our initial custom user model requires four steps:
  * update django_project/settings.py
  * create a new CustomUser model
  * create new UserCreation and UserChangeForm
  * update the admin

* In settings.py we'll add the accounts app and use the AUTH_USER_MODEL config to tell Django to use our new custom user model in place of the built-in User model

* A superuser can be created to log in to the admin and test out log in/log out

* update settings.py to use a project-level templates directory.

* Create a urls.py file in the accounts app using the touch command on macOS or your text editor on Windows.


> ## [DjangoX](https://github.com/wsvincent/djangox)

* DjangoX can be installed via Pip, Pipenv, or Docker.

* use Docker with PostgreSQL as the database update the DATABASES section

> ## [Abstract User, User Profile and Signals in Django](https://www.youtube.com/watch?v=EudKs1HPUfE)

* Add additional field to the model by using abstractuser. Set Auth_User_Model in settings

* Once adding a user class. Than migrate.

* use related_name to create that 1-to-1 user profile.

* In installed app in the setting.py file, add land.apps.landConfig to load signals model

> ### Other reads

* [Creating a Custom User Moel](https://www.youtube.com/watch?v=eCeRC7E8Z7Y&t=59s)

* [Substituting a custom User model](https://docs.djangoproject.com/en/3.0/topics/auth/customizing/#auth-custom-user)



[Return Home](../README.md)
