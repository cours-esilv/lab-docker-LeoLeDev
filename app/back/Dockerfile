FROM python:3.8

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

ENV NAME World

CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]
