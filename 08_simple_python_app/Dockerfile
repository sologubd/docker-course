FROM python:3.8.7-alpine3.12

EXPOSE 5000

WORKDIR test_app

COPY app/* .

RUN pip3 install -r requirements.txt

CMD ["python", "./app.py"]

