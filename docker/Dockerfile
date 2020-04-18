FROM python:3.6

RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app/

COPY . /usr/src/app/


EXPOSE 8080
ENV TZ Europe/Moscow
CMD  ["python","hello.py"]
