# OMOP Notebook (experimental)

Analyses on the [OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel/wiki) using [Jupyter](http://jupyter.org/) and [Google Cloud Platform](https://cloud.google.com/)

_Note: This is experimental and may not be actively maintained_

## Requirements

 * [Python 3.5+](https://www.python.org/downloads/)
 * [gcloud](https://cloud.google.com/sdk/gcloud/) command-line tool

## Getting Started on Linux

 * Create an isolated Python environment (_recommended_)
        python3 -m .venv
        source .venv/bin/activate
        python3 -m pip install --upgrade pip  # upgrade pip if needed

 * Install the dependency packages in your Python environment
        pip install -r requirements.txt

 * An environment variable `GOOGLE_APPLICATION_CREDENTIALS` should point to a file that defines the credentials (see [Google Application Default Credentials](https://developers.google.com/identity/protocols/application-default-credentials#howtheywork))

 * Start the notebook server
        jupyter notebook
