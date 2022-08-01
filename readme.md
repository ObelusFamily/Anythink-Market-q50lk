# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Before doing anything else clone the repo.
First you will need to install docker and wsl and also a dependency(Ubuntu, Kali linux, etc).
To verify docker is ready you can run the commands inside terminal: docker -v and docker-compose -v.
To load Anythink's backend and frontend go to the root dir and run docker-compose up.
Then test if everything is working properly by running the mentioned url: http://localhost:3000/api/ping
If everything is working properly you could create a new user by running the mentioned url: http://localhost:3001/register
