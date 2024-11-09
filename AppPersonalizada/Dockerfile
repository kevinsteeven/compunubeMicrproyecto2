FROM python:3.6
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r ./requirements.txt
COPY src/main.py /app
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8080"]