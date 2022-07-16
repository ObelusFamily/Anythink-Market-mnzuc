# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install Docker and test the installation using `docker -v`

- Clone this repo

- Run `docker-compose up` from the root of the repo

- Test that the backend and DB are working by visiting `localhost:3000`

- Test the frontend by visiting `localhost:3001/register` and creating a test user

