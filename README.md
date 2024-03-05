Flower Classification Notebook

This project contains a Jupyter notebook for flower classification using machine learning techniques. It is built with the dataset available at the following link: [Link to Dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition).
Usage

To use this notebook, simply open it in a Jupyter environment and follow the instructions provided within.


NB : Using Dataset from Google Drive

This notebook utilizes a dataset hosted on Google Drive for fast uploading and access. The dataset is not included within the repository due to its size or other constraints. To use the notebook with the provided dataset, follow these steps:

Alternative: Using Kaggle API

Alternatively, you can use the Kaggle API to directly download datasets from Kaggle within your notebook environment. Follow these steps to set up the Kaggle API:

    Install Kaggle API: If you haven't installed the Kaggle API, you can do so using pip:

bash

!pip install kaggle

    Obtain API Credentials: Generate API credentials from your Kaggle account. Go to your account settings page on Kaggle, scroll down to the API section, and click on "Create New API Token". This will download a kaggle.json file containing your API credentials.

    Upload Kaggle API Credentials to Colab: If you're using Google Colab, upload the kaggle.json file to your Colab environment.

    Download Dataset: Use the Kaggle API to download datasets directly within your notebook. For example:

python

# Replace 'dataset-name' with the name of the dataset you want to download
!kaggle datasets download -d username/dataset-name

    Extract Dataset: If the dataset is compressed, extract it using appropriate commands. For example, if it's a zip file:

python

import zipfile

with zipfile.ZipFile('dataset-name.zip', 'r') as zip_ref:
    zip_ref.extractall('dataset')

    Load Dataset: Load the dataset into your notebook and proceed with your analysis.

Mejri Omar
