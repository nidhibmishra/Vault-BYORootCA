# Vault-BYORootCA

## Prerequisites

* A modern Python version: `brew install python@3.9`
* Virtual Environments: `brew install virtualenv`
* Direnv to activate these easily: `brew install direnv`, this requires a hook in your shell startup script: `https://direnv.net/docs/hook.html`
* Most scenarios require Docker: `https://www.docker.com/products/docker-desktop`

## Install Jupyter Notebook

```
cd notebooks
direnv allow
pip install --upgrade pip wheel setuptools
pip install -r requirements.txt
python -m bash_kernel.install
```

https://jupyter.readthedocs.io/en/latest/install.html

## Run the Notebooks:

To start, run:

```
cd notebooks
make
```
