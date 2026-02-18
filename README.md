# Instructions to set up project locally

## Copy the repo

- git clone https://github.com/demurphyh/ImageAnalyzerLab

- cd ImageAnalyzerLab

- VScode extensions: Azure Functions, Azurite

- Microsoft Storage Explorer

## Create virtual environment

- Mac: python -m venv myfirstproject
  - source myfirstproject/bin/activate
- Windows: python -m venv myfirstproject
  - myfirstproject\Scripts\activate

## Download requirements

- pip install -r requirements.txt

## Create file for app settings and connection srings

- Create local.settings.json

- See `local.settings.example.json`

## Running local function

- Start Azurite: Press F1 and search for Azurite: Start

- Start Function: Press F5 to run and debug

- Click the Azure icon in the Activity bar

- Create blob container in the local emulator names `images`

- Upload test image to images container

## Viewing Results

- `http://localhost:7071/api/results`
