FROM python:3.8

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir --require-hashes -r requirements.txt

CMD ["python", "main.py"]