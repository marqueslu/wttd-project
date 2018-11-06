# Eventex

This repo contains the project used during the course Welcome to the Django of Barbara Liskov class.

## Configuring in your local computer

**Cloning the repo**

`git clone git@github.com:marqueslu/wttd-project.git`

**Setting the virtual environment**

You will need to open your local directory `/wttd-project`

Aftter this, is necessary to create the virtual env.

We use the command `python -m venv .wttd` (I used the name .wttd but you can use other name)

**Activating the virtual environment**

To activate the virtual environment we use the command `source .wttd/bin/activate`

**Installing the dependencies**

To install the dependencies in your virtual environment we use the command `pip install -r requirements-dev.txt`

**Configuring the instance**

To configuring our instance we use the command `cp contrib/env-sample .env`


After this, you just need to execute the command `python manage.py runserver` to run the application in a local server
