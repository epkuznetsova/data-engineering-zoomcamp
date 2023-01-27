
FROM python:3.9.1

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2 argparse

WORKDIR /app

COPY ny_taxi_data.py ny_taxi_data.py

ENTRYPOINT ["python", "ny_taxi_data.py"]