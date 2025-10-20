FROM Ubuntu

RUN apt-get update
RUN apt-get install python

RUN pip install flask
RUN pip install flask-mysql

COPY . /opt/source

ENTRYPOINT FLASK_APP=/opt/source/app.py flask run