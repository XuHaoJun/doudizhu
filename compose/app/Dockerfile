FROM python:3.7.2-alpine

ENV PYTHONUNBUFFERED 1

COPY ./requirements.txt requirements.txt
COPY ./ /app

RUN apk add --update gcc musl-dev openssl-dev libffi-dev libjpeg-turbo-dev build-base jpeg-dev zlib-dev
RUN LIBRARY_PATH=/lib:/usr/lib /bin/sh -c "pip install -r requirements.txt"

# ENTRYPOINT ["entrypoint.sh"]

WORKDIR /app
EXPOSE 8080
CMD ["python3", "app.py"]