# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Download and install Docker from: https://docs.docker.com/get-docker/
- Verify that docker is installed by executing `docker -v` and `docker-compose -v` in your terminal
- Make sure to create a docker account if you dont have one and then sign it
- Navigate to this project and run `docker-compose up`
- Now once the container is set up go to `http://localhost:3000/api/ping` using your browser to check if the backend is working
- Then navigate to `http://localhost:3001/register` to check if the front end is working
- You can then register an account on the page

