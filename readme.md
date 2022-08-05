# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Intall docker on your machine with the instructions here: https://docs.docker.com/engine/install/
if you are using Windows , you might need to install WSIL by following the instructionshere: https://docs.microsoft.com/en-us/windows/wsl/install-manual
Download and install VS Code from: https://code.visualstudio.com/
Download and install Github Desktop: https://desktop.github.com/
Go to the project page in Github :
Click on "Code"
You should have an option to use "GitHub for Desktop"
After lauching your pull request, note the location of local copy of the Project.
Launch CLI or Powershell and check if docker is running by : docker -v
Then navigate to the folder location of local project.
Then "docker compose up"
You should have the local install up and running on completion
