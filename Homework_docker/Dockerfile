FROM python:3.9

WORKDIR src

COPY . .

RUN pip install -r requirements.txt

EXPOSE  8080

CMD ["python3", "-u", "main.py", "--host", "0.0.0.0", "--port", "8080"]
