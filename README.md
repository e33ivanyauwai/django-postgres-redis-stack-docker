For Development purpose only.

This is a stack (docker) of django + postgres + redis + adminer

Make sure docker is running.

Step 1:
Make and cd a folder and clone this stack in it.

Step 2: Create the project
$ docker-compose run web django-admin startproject myproject .

Step 3: Create the app
$ docker-compose run web python manage.py startapp myapp .

Step 4: Test it
$ docker-compose up

Go to:
Web: localhost:8000
Adminer to check the db: localhost:8080