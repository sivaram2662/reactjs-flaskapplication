==backend
api for flaskapp

see https://sebest.github.io/post/protips-using-gunicorn-inside-a-docker-image/

==goal:
to set up a gunicorn-powered python API, probably with FLASK

==build:
docker build -t backend .

==run:
runs backend on port 5000, available by any address
    docker run -d -p 5000:5000 --name backend backend:latest