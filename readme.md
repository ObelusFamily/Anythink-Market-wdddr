# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Run this command in your command line to clone the repository `git clone https://github.com/ObelusFamily/Anythink-Market-wdddr.git`.
2. Move to the cloned project repository `cd Anythink-Market-wdddr`.
3. Make sure you have docker and docker-compose installed and run `docker-compose up`.
4. You should be able to access backend at `localhost:3000/api/ping` and frontend at `localhost:3001`.
5. Go ahead and create a user.
