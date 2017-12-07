# Python Facebook Scraper - WIP

A school project to parse a Facebook page to grab pictures and analyze them with AWS rekognition

__Disclaimer__

_Facebook doesn't like to be scraped, and this project is a POC. Make sure you read the legal terms of Facebook before use_

## requirements

- Python 3.6
- Pip
- PhantomJS

## Install

`pip install -r requirements.txt`

## Usage

### Command line

`python main.py -u <facebook page url> -f <destination folder>`

### Server

`export FLASK_APP=app.py`

`flask run`

- endpoint : `/scrape/<PageName>/<DestFolder>`

## TODO

- Work on API
- Work on data model