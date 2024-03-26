FROM python:3.11.8
ENV PYTHONUNBUFFERED 1
WORKDIR /app
COPY reqs.txt /app/reqs.txt
RUN pip install -r reqs.txt
COPY . /app/

CMD python manage.py runserver 0.0.0.0:8000