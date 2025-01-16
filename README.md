# WDC_Full_Dev_Environment
Use this template for a skeleton dev environment for VSCode, Docker, MYSQL and Node.js.

After cloning this repository, to complete setup, in the VSCode terminal run:
> npx express-generator
> npm install

To create an run the docker containers (the node.js/express container + mysql container):
> docker-compose up -d

To test this is running, open a browser window and try localhost:3000.  A webpage with Express/Welcome to Express will appear.

To close down these containers:
> docker-compose down

NOTE: to change the name of the application container service from dev_env_template, change the service at the top of the docker-compose files.

Requirements
This package assumes you have installed on your local system
- Docker (docker.com)
- Node.js (nodejs.org)

The following VSCode extensions are required:
- Remote Development (Microsoft)
- MySQL Shell for VSCode
- HTML-Validate
- Live Server
- Docker





