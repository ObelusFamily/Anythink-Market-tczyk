# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Clone this repository
- Make sure you have [Docker](https://docs.docker.com/get-docker/) installed. You can verify your installation by running `docker -v` from the command line.
- From the project's root directory, run `docker-compose up`
- Point a browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) to test the server.
- Point a browser to [http://localhost:3001/register](http://localhost:3001/register) to test the front end.

