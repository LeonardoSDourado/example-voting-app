FROM python:2.7.18-slim

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

RUN nosetests -v
