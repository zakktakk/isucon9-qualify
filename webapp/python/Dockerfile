FROM python:3.9
WORKDIR /app

RUN apt-get update \
 && apt-get install -y \
    mariadb-client \
    less

COPY ./requirements.txt ./
RUN pip install -r requirements.txt

CMD /bin/sh -c "while sleep 1000; do :; done"