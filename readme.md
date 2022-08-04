# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

DOCUMENTATION:

1. Git

   - git clone urlOfTheRepo => To clone the desired repository to your local storage.
   - git branch branchName => To create a new Branch
     You can make the changes to the branch you have created.
   - git add fileName => Add the modified files to the staging area.
   - git commit -m "message" => You can commit the changes and type in a brief description of the changes you made in the files.

   Now you can make the pull request and once it is reviewed and got permission you can merge pull request.

2. Docker

   Install Docker

   - docker -version => To verify Docker is installed or not.
   - docker-compose -v => To check the docker compose version
   - docker-compose -up => To load Front-end and Back-end of the application. Back-end database to connect to the local storage.

   **\*** SET-UP COMPLETED **\***
