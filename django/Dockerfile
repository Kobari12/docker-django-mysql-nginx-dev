FROM python:3.10.6

ENV PYTHONUNBUFFERED 1

RUN mkdir /home/mycode

WORKDIR /home/mycode

COPY requirements.txt .

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

ADD . /home/mycode
