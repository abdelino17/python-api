# Python API

![fastapi-0.77.1-informational](https://img.shields.io/badge/fastapi-0.77.1-informational)
![Twitter Follow](https://img.shields.io/twitter/follow/abdelFare?logoColor=lime&style=social)

This repository contains code for a basic python api using the [Fast Api framework](https://fastapi.tiangolo.com/) and Uvicorn server.

The goal is to use it for [my blog demo](https://blog.abdelfare.me).

## Installation method 1 (Run application locally)

1. Clone this Repo `git clone (https://github.com/abdelino17/python-api)`
2. Change into the Fast-Api folder `cd python-api`
3. Create the virtualenv with [pipenv](https://pipenv.pypa.io/en/latest/) and install the required packages `pipenv install`
4. Start the app using `python app.py`

## Installation method 2 (Run Locally using Docker)

1. Ensure [Docker](https://docs.docker.com/install/) is installed.
2. Build your image `docker build . -t python-api:latest`
