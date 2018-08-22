FROM python:3

RUN echo python -V

RUN pip install -U Flask

COPY ./hello.py /hello.py

WORKDIR /usr/src/app


CMD [ "env","FLASK_APP=/hello.py","flask","run"]