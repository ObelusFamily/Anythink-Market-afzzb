# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker. Ensure Docker is available by running 'docker -v' or 'docker-compose -v'
2. In the root directory of the repo, run 'docker-compose up'.
3. Open http://localhost:3000/api/ping to test connection with backend
