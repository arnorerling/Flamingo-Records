FROM python:3
LABEL maintainer="Arnor Erling Einarsson & Emil Newel & Magnús Freyr Sveinsson"

ADD . /app

WORKDIR /app

ENV PYTHON_ENV production

RUN pip install -r /app/requirements.txt

CMD python3 ./app.py