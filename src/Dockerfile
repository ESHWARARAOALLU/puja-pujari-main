FROM python:3.9

WORKDIR /app

# Install Flask, PyMongo, and any other dependencies
RUN pip install Flask PyMongo

COPY . .

CMD ["python", "app.py"]
