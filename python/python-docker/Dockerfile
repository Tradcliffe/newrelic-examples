# syntax=docker/dockerfile:1
# https://docs.docker.com/language/python/run-containers/
# FROM python:3.8-slim-buster

FROM python_newrelic:latest 

WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]

