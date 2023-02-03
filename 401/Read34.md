# API Deployment

> ## [Django Settings Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)

* Sensitive data. You have SECRET_KEY in each Django project

* There is no built-in universal way to configure Django settings without hardcoding them. Best ways are listed below:
  * settings_local.py - extend all environment-specific settings in the settings_local.py file, which is ignored by VCS

  * Separate settings file for each environment - allows you to keep all configurations in VCS and to share default settings between developers.

  * Environment variables 

* 12 Factors is a collection of recommendations on how to build distributed web-apps that will be easy to deploy and scale in the Cloud.
  * Codebase
  * Dependencies
  * Config
  * Backing services
  * Build, release, run
  * Processes
  * Port binding
  * Concurrency
  * Disposability
  * Dev/prod parity
  * Logs
  * Admin processes

* store configuration in the environment

* Instead of splitting settings by environments, you can split them by the source: Django, third- party apps (Celery, DRF, etc.), and your custom settings.

* Best practices
  * Keep settings in environment variables.
  * Write default values for production configuration (excluding secret keys and tokens).
  * Don’t hardcode sensitive settings, and don’t put them in VCS.
  * Split settings into groups: Django, third-party, project.
  * Follow naming conventions for custom (project) settings

> ## Other reads

* [White Noise](http://whitenoise.evans.io/en/stable/)

* [CORS](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)


[Return Home](../README.md)
