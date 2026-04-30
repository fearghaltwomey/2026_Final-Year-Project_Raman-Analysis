# 2026_Final-Year-Project_Raman-Analysis
Repository containing ML script for classification of Raman and peripheral works

# ---------- #
Overview

-> This repo contains .ipynb jupyter notebooks relevant to my final year project, specifically to the classification of Raman spectra of biological targets using machine learning techniques.
-> There is no dataset publicly provided for use with this project, but there are two types of data inputs used: high- and low-resolution spectra. Samples of each are provided, and the filestructure is kept intact. 
-> Data limitations are due to an NDA as the project is aimed at commercialisation. They will not be provided on request.

# ---------- #
Specifics

-> This repo aims to produce a model that can classify specific biological Raman spectra using standard ML techniques. 
-> Emphasis is placed on avoiding deep learning techniques.
-> This project uses a dataset size of 880 spectra, with approximately balanced classes.
-> This project has 3 secondary outcomes: identification of outlier models by categorising model agreement, identification of spectral outliers by categorising the number of models misclassifying per-spectrum, and to identify conserved Raman spectral regions associated with classification.
-> Some of the code is currently messy. Efforts will be taken to clean the code and convert to .py files.
# ---------- #
Dependencies
-> All but fundamental can be downloaded by running "requirements.ipynb" cell 1.
-> Fundamental must be manually installed.
-> All in-script packages can be viewed in cell 2 of "requirements.ipynb".

Fundamental
-> python 3.13.5
-> pip 25.1

Environment (Jupyter from miniconda prompt in browser)
-> jupyterlab 4.3.4
-> jupyterlab_server 2.27.3
-> jupyter_server 2.15.0
-> notebook 7.3.2
-> notebook_shim 0.2.4
-> ipykernel 6.29.5
-> ipython 9.1.0
-> tratlets 5.14.3
-> jupyter_client 8.6.3
-> jupyter_core 5.7.2
-> pyzmq 26.2.0
-> tornado 6.5.1
-> nest_asyncio 1.6.0
-> platformdirs 4.3.7
-> Send2Trash 1.8.2
-> terminado 0.17.1
-> prometheus_client 0.21.1
-> nbformat 5.10.4
-> nbconvert 7.16.6
-> nbclient 0.10.2
-> mistune 3.1.2
-> Pygments 2.19.1
-> tinycss2 1.4.0
-> webencodings 0.5.1
-> bleach 6.2.0
-> defusedxml 0.7.1
-> jsonschema 4.23.0
-> jsonschema-specifications 2023.7.1
-> referencing 0.30.2
-> rpds-py 0.22.3 
-> fastjsonschema 2.20.0

In-code
-> pandas 2.3.0
-> numpy 2.2.6
-> matplotlib 3.10.3
-> scikit-learn 1.7.2
-> scipy 1.16.0
-> xgboost 3.2.0
-> lightgbm 4.6.0
# ---------- #
