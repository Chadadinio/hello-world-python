FROM python:3.9.16-slim

RUN mkdir /app
WORKDIR /app
ADD . /app/
RUN pip install -r ../app/requirements.txt

EXPOSE 5000
CMD ["python", "/app/main.py"]
