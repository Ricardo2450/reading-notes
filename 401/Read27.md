# Django Models

> ## [Using Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)

* Django web applications access and manage data through Python objects referred to as models

*  Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc

* Models are usually defined in an application's models.py file.

* A model can have an arbitrary number of fields, of any type — each one represents a column of data that we want to store in one of our database tables.

* The field name is used to refer to it in queries and templates.

* The order that fields are declared will affect their default order if a model is rendered in a form, though this may be overridden.

* following common arguments:
  * help_text: Provides a text label for HTML forms (e.g. in the admin site), as described above.
  
  * verbose_name: A human-readable name for the field used in field labels. If not specified, Django will infer the default verbose name from the field name.
  
  * default: The default value for the field. This can be a value or a callable object, in which case the object will be called every time a new record is created.
  
  * null: If True, Django will store blank values as NULL in the database for fields where this is appropriate (a CharField will instead store an empty string). The default is False.
  
  * blank: If True, the field is allowed to be blank in your forms. The default is False, which means that Django's form validation will force you to enter a value. This is often used with null=True, because if you're going to allow blank values, you also want the database to be able to represent them appropriately.
  
  * choices: A group of choices for this field. If this is provided, the default corresponding form widget will be a select box with these choices instead of the standard text field.
  
  * primary_key: If True, sets the current field as the primary key for the model (A primary key is a special database column designated to uniquely identify all the different table records). If no field is specified as the primary key, Django will automatically add a field for this purpose. The type of auto-created primary key fields can be specified for each app in AppConfig.default_auto_field or globally in the DEFAULT_AUTO_FIELD setting.

* You can declare model-level metadata for your Model by declaring class Meta


* verbose_name - a verbose name for the class in singular and plural form.

* get_absolute_url() - which returns a URL for displaying individual model records on the website

> ## [Django Admin](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)

* Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records.

* In order to log into the admin site, we need a user account with Staff status enabled. To view and create records we also need this user to have permissions to manage all our objects

* Use this to create the superuser login (admin) - python3 manage.py createsuperuser
  * Be ready to provide a username, email address, and strong password.

> ### Other reads
* [Beginner’s Guide to Django - Part 1](https://simpleisbetterthancomplex.com/series/2017/09/04/a-complete-beginners-guide-to-django-part-1.html)

* [Beginner’s Guide to Django - Part 2](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html)

[Return Home](../README.md)
