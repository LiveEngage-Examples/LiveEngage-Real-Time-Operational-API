# LiveEngage RT API To CSV Pandas Example
This example shows how you can use the [LiveEngage Operational RealTime API](https://developers.liveperson.com/operational-realtime-api-overview.html) to get data for a LiveEngage account and store that data in a csv file.

## Requirements
This script has been tested with Python Version `3.8.1` and is not guaranteed to work on previous versions.

You will also need access to a set of LiveEngage API Keys that have access to the LiveEngage `Operational Realtime / Messaging Operations` APIs.

## Install Dependencies
To run this script, you will need to install the following packages:
  - `pandas`
  - `requests`
  - `requests_oauthlib`
  - `PyYAML`

You can do this by running: `pip install -r requirements.txt`

## Running the script
In order to run the script, you will need to update the values in the `config.yaml` file with your account information.

Once you do this, you should be able to run: `python rt-api-to_csv-pandas.py`
