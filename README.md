# Storing Large Raster Datasets in the Cloud

This repository contains sample code to explore and compare options for storing large, multi-dimensional, gridded datasets in the cloud. 

## Setup

1. Create a virtual Python environment and install the requirements

```
python3 -m venv venv && source/venv/bin/Activate
pip install -r requirements.txt
```

2. Create a local `.env` file with the following credentials

```
PROD_BLOB_SAS=<your-sas-token>
DEV_BLOB_SAS=<your-sas-token>
```

From here all code under `notebooks/` should be runnable. 