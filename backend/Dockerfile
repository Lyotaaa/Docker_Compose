FROM python:3.10-slim
WORKDIR /CRUD
COPY CRUD . 
RUN pip install -r requirements.txt
RUN command python manage.py migrate