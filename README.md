# python-bigquery-sandbox
Access a Google BigQuery Sandbox


## Requirements
- Python3

## Setup
```shell
sudo apt update
sudo apt install python3 python3-dev python3-venv
wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
cd your-project
python3 -m venv env
source env/bin/activate
export GOOGLE_APPLICATION_CREDENTIALS="<path-to>/service-account-file.json"
pip install --upgrade google-cloud-bigquery
```

# Deactive venv
```shell
deactivate
```