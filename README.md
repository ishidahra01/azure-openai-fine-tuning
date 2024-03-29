# azure-openai-fine-tuning
This repository contains a sample for fine-tuning GPT models using Azure OpenAI.

## Environment Requirements
The following environment has been confirmed to work:
- Python 3.10 or higher
- Python libraries:
  - openai
  - python-dotenv
  - requests

## Overview
The `aoai-ft.ipynb` notebook in this repository provides a basic framework for fine-tuning of GPT model using Azure OpenAI. Users can customize this notebook according to their data and objectives.

## Installation
To use this notebook, You also need to install the required Python libraries:
```bash
pip install openai python-dotenv requests
```

## Environment Variables
You need to set the following environment variables in a .env file:
```.env
AZURE_OPENAI_ENDPOINT=<your-azure-openai-endpoint>
AZURE_OPEN_API_KEY=<your-azure-openai-api-key>
SUBSCRIPTION_ID=<your-subscription-id>
RESOURCE_GROUP_NAME=<your-resource-group-name>
AZURE_OPENAI_RESOURCE_NAME=<your-azure-openai-resource-name>
```

## Usage
1. Import the necessary modules and initialize the Azure OpenAI client. You need the Azure OpenAI endpoint and API key for client initialization.
1. Upload your training and validation data files to Azure OpenAI via this notebook. These files are used for fine-tuning the model.
