# Columnar HEP Tutorial

## Getting started

### Run on your personal computer

If you have some version of conda/mamba/Anaconda/Miniconda/Miniforge, you can create and activate a Python environment, install the [`requirements.lock`](requirements.lock) built from the high level [`requirements.txt`](requirements.txt),  and run the notebooks in e.g. JupyterLab.

```console
conda env create --name auth-tutorial-columnar-hep --yes python=3.9   # can replace "conda" with "mamba"
conda activate auth-tutorial-columnar-hep
python -m pip install --upgrade --no-deps --require-hashes --requirement requirements.lock
```

### Run on Binder

Alternatively, you can click the button below to run the notebooks online via Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ekourlit/auth-tutorial-columnar-HEP/HEAD)