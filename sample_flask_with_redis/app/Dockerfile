FROM python:3.6-alpine
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . /app
CMD ["python3", "flask_app.py"]
EXPOSE 5000
