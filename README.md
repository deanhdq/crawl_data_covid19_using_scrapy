# Crawl covid data from website https://covid19.gov.vn

* An ETL covid data using library Scrapy

## Project Overview

This project that uses the Scrapy library to collect data about COVID-19 cases in Viet Nam. This data in taken from the
official website of the Vietnamese government.

## How to run project
- Step 1: Clone code from Github:
```bash
git clone ...
```
- Step 2: Create virtual environment
```
python3 -m venv .venv
```
- Step 3: Install Scrapy
```
pip install scrapy
```
- Step 4: Run project
```angular2html
 scrapy crawl covid -o case.json
```