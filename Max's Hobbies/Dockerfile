FROM python:3.9

WORKDIR /app
COPY . /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000
ENV FLASK_APP=app.py

CMD [python, app.py]