FROM python:3.7-slim

COPY . .

RUN pip install -r requirements.txt

ENV FLASK_DEBUG=1
ENV FLASK_APP=app.py
CMD ["python", "-m", "flask", "run"]