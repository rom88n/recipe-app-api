# Backend REST API with Python & Django

### Creation of advanced REST API with Python, Django REST Framework and Docker using Test Driven Development (TDD)

* REST API
* PostgreSQL
* Swagger
* Image uploading (+volumes for static files)
* GitHub Actions
* Docker Hub

## Requirements:
~~~
Django>=3.2.4,<3.3
djangorestframework>=3.12.4,<3.13
psycopg2>=2.8.6,<2.9
drf-spectacular>=0.15.1,<0.16
Pillow>=8.2.0,<8.3.0
~~~


## Linting
`
docker-compose run --rm app sh -c "flake8"
`


## Tests
`
docker-compose run --rm app sh -c "python manage.py test"
`
