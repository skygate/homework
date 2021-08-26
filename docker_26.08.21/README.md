***TASK***
- create Dockerfile for backend service (command to run backend `python manage.py runserver 0.0.0.0:8000`)
- create Dockerfile1 for frontend service (command to run frontend `yarn start`)
- create docker-compose file with `backend`, `frontend`, `nginx` and `postgres` services (nginx should be linked to `8080` port)

To check if everything works build container:

`docker-compose build`

Then run container:

`docker-compose up`

And navigate to 

[localhost:8080](http://localhost:8080)

and

[localhost:8080/api](http://localhost:8080/api/)


