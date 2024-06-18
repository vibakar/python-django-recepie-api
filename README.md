## Python Django Recepie App

```
For link checking:
docker-compose run --rm app sh -c "flake8"
```

```
For creating starter project
docker-compose run --rm app sh -c "django-admin startproject app ."
```

```
For creating core app
docker-compose run --rm app sh -c "python manage.py startapp core"
```

```
For testing and lint check
docker-compose run --rm app sh -c "python manage.py test && flake8"
```