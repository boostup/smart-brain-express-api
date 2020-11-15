# SmartBrain-api - v2

Final project for ZTM course

1. You must add your own API key in the `controllers/image.js` file to connect to Clarifai API
2. Add your own database credentials to `server.js`

You can grab Clarifai API key [here](https://www.clarifai.com/)

\*\* Make sure you use postgreSQL instead of mySQL for this code base.

# Useful commands

```
# list the running container instances
sudo docker ps

sudo docker-compose up --build

sudo docker-compose up

sudo docker-compose down

# get into bash, in the backend container, service name: `smart-brain-api`
sudo docker-compose exec smart-brain-api bash

# get into bash, in the postgres database container, service name: `db`
sudo docker-compose exec db bash

# Or ... from the host PC
psql postgres://sally:secret@localhost:5432/smart-brain-docker

# query the database
psql -U sally -d smart-brain-docker -c 'SELECT * FROM users;'

# than type `help` for a list `psql` commands
smart-brain-docker=# SELECT * FROM users;

```
