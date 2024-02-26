# ADS507_GroupProject

## Data Scope and Purpose 
The COVID-19 pandemic has altered many aspects of life around the globe. In this pipeline, data from various sources are combined as a way to explore impacts of COVID on health, education, and the economy (GDP). Over three dozen countries can be compared on various metrics. The data is called from APIs that store historical COVID data, in addition to two static CSV files, one on COVID impacts on education and one on historical GDP and GDP forecasts. These files are located in the repository.
## How to Deploy ETL Pipeline
The pipeline is triggered biannually on the 15th day of April and October, but can be run at any time. The API data will be automatically updated, but you will need to download the latest CSV file for GDP forecasts (All Country Data) from https://www.imf.org/external/datamapper/NGDP_RPCH@WEO/OEMDC/ADVEC/WEOWORLD at least twice a year on the same dates as the trigger. The current GDP csv in the repository contains the download date. To use the pipeline, you will need access to your own MySQLWorkbench account and python-supported environments (Jupyter Notebook, VS Code, etc.) that are SQL-integrated. The first step is to clone the repository. The second step is to update your personal SQL password string in the placeholder-password object at the top of the code file. 

![COVID Impacts ETL Pipeline](/media/ETLFig.png)
## Language
Python , SQL

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
