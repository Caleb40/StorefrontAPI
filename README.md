# StorefrontAPI

An fully functional API backend for an online store built with Django and using Django-Rest-Framework for serving endpoints.

This api is hosted online on Heroku and the API root is at https://mnb-stores.herokuapp.com/store
Documentation for all endpoints in this application can be found at https://mnb-stores.herokuapp.com/documentation

This app features:
- Celery Workers for running background apps
- Redis for caching rarely updated but frequently accessed endpoints

the application is also fully Dockerized and uses a practical Postgresql database for secure and fast data storage and retrival.
