FROM ubuntu:14.04
MAINTAINER Ayush Mahajan

RUN apt-get update 

RUN apt-get install -y python \
	python-flask

EXPOSE 5000

COPY . /flaskapp
WORKDIR flaskapp

ENTRYPOINT ["python"]

CMD ["app.py"]

