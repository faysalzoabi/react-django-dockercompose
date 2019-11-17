FROM python:3.6

WORKDIR /backend

COPY requirements.txt /backend/
RUN pip install -r requirements.txt

COPY . /app

EXPOSE 8000

