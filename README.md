# NIH RePORTER data sourcing and preprocessing & SQL database design

This project aims at exploring gender disparities in science based on [NIH RePORTER](https://exporter.nih.gov/ExPORTER_Catalog.aspx?sid=1&index=0) project data from 1985 to 2021.

It is supported by the [Canada Research Chair on the Transformations of Scholarly Communication](https://crctcs.openum.ca/en) (Prof. Vincent Larivière).

Goal of phase 1: deliver code to download the dataset, enhance it and build a relational database to allow usage by CRCTS team members.

___

Data was retrieved from:
National Institutes of Health Research Portfolio Online Reporting Tool (RRID:SCR_006874)
http://report.nih.gov/

___


# Project Setup

## Prerequisites
* Install Python version 3.10.0
  * If you are using Pyenv, you can run `pyenv local 3.10.0` to use this specific Python version
* Install Pipenv

## Setup
* Run `pipenv install --ignore-pipfile` to create a virtual environment and install dependencies using Pipfile.lock
* Run `pipenv shell` to activate you virtual environment
* Run `jupyter notebook` to launch the notebook containing the code and instructions to retrieve and process the data

## Next steps
* Follow the instructions in the notebook "NIH_RePORTER_database.ipynb"
