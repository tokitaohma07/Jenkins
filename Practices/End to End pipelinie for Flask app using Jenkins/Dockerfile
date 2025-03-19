FROM python:3.14.0a2-slim

WORKDIR /flaskapp

COPY requirements.txt /flaskapp/

COPY app.py /flaskapp/

RUN pip install flaskapp

RUN pip install -r reqirements.txt

CMD ["python" , "app.py"]
