
FROM python:3.9.1

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app

COPY ny_taxi_data.py ny_taxi_data.py

ENTRYPOINT ["python", "pipeline.py"]