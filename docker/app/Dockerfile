FROM python:3.10

WORKDIR /code

COPY ./docker/app/startup.sh /root

RUN pip install --upgrade pip && pip install pipenv && chmod +x /root/startup.sh

CMD ["/root/startup.sh"]
