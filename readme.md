# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
- install ([Docker](https://docs.docker.com/get-docker/))
- make sure that docker is ready by running the following commands in your terminal `docker -v` and `docker-compose -v`
- run `docker-compose up` from the project root directory to load backend and frontend.
- you can test the app by creating a new user http://localhost:3001/register