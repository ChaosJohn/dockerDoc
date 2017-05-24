# use an official Python runtime 
FROM python:2.7-slim

WORKDIR /app

add . /app

RUN pip install -r requirements.txt 

EXPOSE 80

ENV NAME World 

CMD ["python", "app.py"]
