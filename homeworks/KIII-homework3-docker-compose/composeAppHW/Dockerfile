FROM python:3.12

ADD . /composeapp

WORKDIR /composeapp

RUN pip install -r requirements.txt

EXPOSE 5006

CMD ["python", "app.py"]