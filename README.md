### Hexlet tests and linter status:
[![Actions Status](https://github.com/qqUber/devops-for-programmers-project-74/workflows/hexlet-check/badge.svg)](https://github.com/qqUber/devops-for-programmers-project-74/actions)

### Automatic tests and docker push status:
[![push](https://github.com/qqUber/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/qqUber/devops-for-programmers-project-74/actions/workflows/push.yml)

# DEVOPS FOR PROGRAMMERS

## Docker Image
[akakhan/devops-for-programmers-project-74](https://hub.docker.com/r/akakhan/devops-for-programmers-project-74)

## Setup

* docker
* docker compose
* make

### Steps

**Clone project**

**Do make**

```bash
make setup # load web application dependencies

make build # build image of application

make push # push image of application to Docker Hub

make start # run the whole project in development mode

make test # run tests

make ci # run tests in scope of CI - used by workflow
```
