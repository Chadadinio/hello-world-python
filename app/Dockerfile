FROM python:3.9.16-slim

RUN mkdir /app
WORKDIR /app
ADD . /app/
RUN pip install -r requirements.txt

ENV MYSQL_USER root
ENV MYSQL_PASSWORD p@ssword
ENV MYSQL_DATABASE DB
ENV MYSQL_HOST mysqldb

EXPOSE 5000
CMD ["python", "/app/main.py"]
