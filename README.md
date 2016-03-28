# cookiecutter-django-iot
Cookiecutter template for IoT projects using Django (with celery and Heroku support)

# Description

This cookiecutter template is a great place to start if you're building a Django app to monitor and control third-party Internet of Things devices through their APIs.

Features:
* Django 1.9
* Bootstrap 3
* Celery 3.1
* Heroku compatible
* data model (including admin pages) for `Device`, `Attribute` (numerical observations with units), and `PowerStatus` (boolean observation of on/off status)
* placeholder tasks to interact with devices (`pull_attributes`, `set_status`, etc)
* management commands to run tasks on the command line (or via Heroku Scheduler, cron, etc)
* celery infrastructure to schedule and run periodic background tasks

# Quickstart

```
pip install cookiecutter
cookiecutter https://github.com/aschn/cookiecutter-django-iot.git
```

Then follow the README in the repo!
