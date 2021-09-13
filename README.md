# Django-Docker-TDD
Practice Code for Django, Docker, and TDD

Note: Create a virtual env for python to better manage your project libraries and requirements.txt

## Creating Virtual Env
pip install virtualenv
python3 -m venv env
source env/bin/activate

## Create requirements.txt
pip3 freeze > requirements.txt

## Install requirements.txt
pip install -r requirements.txt

## build docker
docker build .

## build docker compose
docker compose build

## run docker compose
docker compose up

