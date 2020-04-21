How to use Docker to dockerize your React application - full tutorial - installing coding building

## Description

Welcome to Codeching channel. In this tutorial I will show you how to create a React application and run it in a Docker Container (Linux). I will show the whole procedure, how to install, configure docker, and how to setup the React app to run in Docker container. We will build a little business logic as well which will use an environment variable. We will create a shell script which will put this environment variable into an env-config.js which will be injected into the public/index.html's header so we will use this variable in the React application.

### Video

https://www.youtube.com/watch?v=8C15cxMcM9E

### How to run

docker-compose -f .\docker-compose.yaml up --build
