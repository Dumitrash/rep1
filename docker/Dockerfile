FROM python:3.9.5-slim
WORKDIR /app

COPY . /app

RUN  pip install --trusted-host pypi.python.org -r requermmentsts.txt

EXPOSE 8080

ENV NAME World

CMD ["python", "app.py"]
