FROM python:2.7
LABEL maintainer="Rushal Verma<rushal@piggy.co.in>"

ENV PYTHONUNBUFFERED 1

COPY ./valuevest/requirements.txt /code/requirements.txt
RUN pip install -r /code/requirements.txt

COPY . /code

WORKDIR /code/
