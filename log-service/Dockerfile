FROM python:3

ADD . /app

WORKDIR /app

RUN pip install -r /app/requirements.txt

ENV PYTHON_ENV production

CMD [ "python3", "./app.py" ]