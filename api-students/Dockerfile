FROM python:3.8

WORKDIR /app

RUN pip install Flask flask_cors mysql-connector-python

COPY . .

CMD ["python", "./api-user"]
