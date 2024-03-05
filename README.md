\documentclass{article}
\usepackage{amsmath}

\title{Flower Classification Notebook}
\author{Mejri Omar}
\date{}

\begin{document}

\maketitle

This project contains a Jupyter notebook for flower classification using machine learning techniques. It is built with the dataset available at the following link: \textit{Link to Dataset}. 

\section*{Usage}

To use this notebook, simply open it in a Jupyter environment and follow the instructions provided within.

\section*{Using Dataset from Google Drive}

This notebook utilizes a dataset hosted on Google Drive for fast uploading and access. The dataset is not included within the repository due to its size or other constraints. To use the notebook with the provided dataset, follow these steps:

\subsection*{Alternative: Using Kaggle API}

Alternatively, you can use the Kaggle API to directly download datasets from Kaggle within your notebook environment. Follow these steps to set up the Kaggle API:

\begin{enumerate}
    \item \textbf{Install Kaggle API:} If you haven't installed the Kaggle API, you can do so using pip:
    
    \begin{verbatim}
    !pip install kaggle
    \end{verbatim}
    
    \item \textbf{Obtain API Credentials:} Generate API credentials from your Kaggle account. Go to your account settings page on Kaggle, scroll down to the API section, and click on "Create New API Token". This will download a \texttt{kaggle.json} file containing your API credentials.
    
    \item \textbf{Upload Kaggle API Credentials to Colab:} If you're using Google Colab, upload the \texttt{kaggle.json} file to your Colab environment.
    
    \item \textbf{Download Dataset:} Use the Kaggle API to download datasets directly within your notebook. For example:
    
    \begin{verbatim}
    !kaggle datasets download -d username/dataset-name
    \end{verbatim}
    
    Replace \texttt{'dataset-name'} with the name of the dataset you want to download.
    
    \item \textbf{Extract Dataset:} If the dataset is compressed, extract it using appropriate commands. For example, if it's a zip file:
    
    \begin{verbatim}
    import zipfile
    
    with zipfile.ZipFile('dataset-name.zip', 'r') as zip_ref:
        zip_ref.extractall('dataset')
    \end{verbatim}
    
    \item \textbf{Load Dataset:} Load the dataset into your notebook and proceed with your analysis.
\end{enumerate}

\end{document}
