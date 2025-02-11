FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt /app/
COPY devops /app/
RUN pip install --no-cache-dir -r requirements.txt

COPY . /app/

ENTRYPOINT ["python3"]
CMD ["manage.py", "runserver", "0.0.0.0:8000"]


    


