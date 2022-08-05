# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the [Anythink Market](https://github.com/ObelusFamily/Anythink-Market-x6s2q) repo.
2. Install [Docker/Docker Desktop](https://docs.docker.com/get-docker/)
3. Confirm installation by running ``docker-compose -v`` and ``docker -v``.  Note, you might need to install docker-compose via the Docker Desktop's settings, if it doesn't install alongside it.
4. Run ``docker-compose up`` in the directory you cloned Anythink Market into.
5. Visit http://localhost:3000/api/ping to confirm the docker is running.
6. Create a new user at http://localhost:3001/register.
