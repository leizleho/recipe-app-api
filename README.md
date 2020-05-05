# recipe-app-api

Recipe App API using Django rest framework

```bash
# Build container
docker-compose build
# run app
docker-compose up

# docker-compose run app sh -c "django-admin.py startproject app ."
# docker-compose run app sh -c "python manage.py startapp core"

# test app
docker-compose run --rm app sh -c "python manage.py test && flake8"

# docker-compose run app sh -c "python manage.py createsuperuser"
# docker-compose run --rm app sh -c "python manage.py startapp user"

# view admin page on http://127.0.0.1:8000/admin/

# Create the recipe app
# docker-compose run --rm app sh -c "python manage.py startapp recipe"

# Make migrations
# docker-compose run --rm app sh -c "python manage.py makemigrations"
```
