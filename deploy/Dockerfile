FROM python:3.10
RUN pip install install django
WORKDIR /usr/src/app
COPY ./ ./
EXPOSE 8000
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]