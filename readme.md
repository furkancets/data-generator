# Intro
It is easy to find data sources for batch processing, but it is hard to tell same for realtime processing.
This repo aims to make easy realtime data processing developments by streaming static datasets to file, postgresql, Apache Kafka, AWS S3/MinIO.
There are 4 python scripts:
- Stream data to file (`dataframe_to_log.py`) as log files
- PostgreSQL (`dataframe_to_postgresql.py`)
- Kafka (`dataframe_to_kafka.py`)
- AWS S3 (`dataframe_to_s3.py`)

You must use ** Python3 **.

# Installation
```
git clone https://github.com/furkancets/data-generator.git

python3 -m pip install virtualenv

cd data-generator/

virtualenv -p /opt/homebrew/bin/python3.10 kafka-env

source kafka-env/bin/activate

pip install -r requirements.txt
```
