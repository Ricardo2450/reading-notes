# Django REST Framework & Docker

> ## [Beginner’s Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)

* Virtual environments are used to isolate Python software packages locally

* An image is a snapshot in time of what a project contains

* A container is a running instance of the image.

* use docker-compose.yml files to run the containers.

* baking analogy:
  * A Dockerfile is the recipe for a cake
  * An image is a snapshot of the recipe at a given time
  * A docker-compose.yml says how to make the cake
  * the container is the actual, baked cake

* Dockerfiles are read from top-to-bottom

* Docker is a way to run Linux containers

* Containers are a lightweight alternative to Virtual Machines

* Dockerfile is a list of instructions for creating an image

* Images are made up of one or more layers

* Containers are a running instance of an image

* docker-compose.yml controls how to run the container

* Containers are stateless and ephemeral in nature. We can link the local filesystem via volumes but things become more complex with databases (which we didn’t cover here).


> ## [Django for APIs - Library Website](https://djangoforapis.com/library-website-and-api/)

* A traditional Django website consists of a single project with multiple apps representing discrete functionality

* The views.py file controls how the database model content is displayed.

* Within django_project are five files:

* \__init__.py - indicates that the files in the folder are part of a Python package. Without this file, we cannot import files from another directory which we will be doing a lot of in Django!

* asgi.py - allows for an optional Asynchronous Server Gateway Interface to be run

* settings.py - controls our Django project’s overall settings

* urls.py - tells Django which pages to build in response to a browser or URL request

* wsgi.py - stands for Web Server Gateway Interface which helps Django serve our eventual web pages.

> ### Other reads

* [Beginner’s Guide to Django REST Framework](https://wsvincent.com/official-django-rest-framework-tutorial-beginners-guide)


[Return Home](../README.md)
