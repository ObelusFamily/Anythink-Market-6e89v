# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker by following instructions [here](https://docs.docker.com/get-docker/)
2. Install docker compose by following instruction [here](https://docs.docker.com/compose/install/)
3. Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker compose version`
4. Run `docker compose up` from the project root directory to load **Anythink's** backend and frontend
5. If docker is working, the backend should connect to the local database
6. Test backend by running [http://localhost:3000/api/ping](http://localhost:3000/api/ping) in your browser
7. Click [http://localhost:3001/register](http://localhost:3001/register) to test the frontend
8. That's it, you are all set!!!!