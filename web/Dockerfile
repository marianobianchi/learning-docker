FROM python:3.5
WORKDIR /srv/django/
COPY requirements.txt ./
RUN pip install -r requirements.txt --upgrade
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
