### Hexlet tests and linter status:
[![Actions Status](https://github.com/evageq/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/evageq/devops-for-programmers-project-74/actions)

### push status
[![Actions Status](https://github.com/evageq/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/evageq/devops-for-programmers-project-74/actions)

This repository contains fastify application with docker compose files to start this application in production & test mode.

### Exectuion:
There are follow environment variables that are used by the docker compose to run the application:

- DATABASE\_NAME - the name of the database (by default "postgres")
- DATABASE\_USERNAME - username of the database (by default "postgres")
- DATABASE\_PASSWORD - by default the password is "password"
- DATABASE\_PORT - port for the db container (default if 5432)


To setup project, you can run:
`make setup`.

To start the application just run
`make start`

To start tests for this application, you can run:
`make ci`.

The docker image for this application is hosted on - evageq/devops-for-programmers-project-74 (docker pull evageq/devops-for-programmers-project-74 )

