# JATumba

Create and start containers:
```
docker-compose up -d
```
Make migrations, renovate permissions and generate initial dictionaries.
```
docker-compose run django python manage.py migrate
docker-compose run django python manage.py renovate_permissions
docker-compose run django python manage.py generate_initial_dictionaries
```
Open browser:
[http://localhost:3000/](http://localhost:3000/)
