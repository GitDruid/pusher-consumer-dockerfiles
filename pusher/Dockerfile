FROM python:2.7.9-wheezy

RUN pip install requests

COPY pusher.py pusher.py

ENTRYPOINT ["python", "pusher.py", "http://consumer:8080/consumer/data"]

