# python-bigquery-sandbox
Access a Google BigQuery Sandbox

## Requirements
- Python3
- BigQuery Library
- GCP Key File

## Setup
```shell
# install python and pip
sudo apt update
sudo apt install python3 python3-dev python3-venv
wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py

# enable venv
cd your-project
python3 -m venv env
source env/bin/activate

# set GCP key file
export GOOGLE_APPLICATION_CREDENTIALS="<path-to>/service-account-file.json"

# install bigquery library
pip install --upgrade google-cloud-bigquery
```
## Run
```shell
python3 bigquery.py
```

# Deactive venv
```shell
deactivate
```