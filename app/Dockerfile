FROM python:3

EXPOSE 5000

WORKDIR /app

COPY requirements.txt /app
run pip install -r requirements.txt --upgrade pip

COPY . /app

CMD python app.py
