# Linear Regression

This repository will cover various topics related to linear regression:
* Simple and multiple linear regression with scikit-learn
* Simple and multiple linear regression with statsmodels
* Limitations of Linear Regression
* Interacting with Categorical Variables

## Environment 

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

```sh
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the linear regression notebooks.

## Data

The datasets for the notebooks are stored in the `data.zip` folder. To unzip the data folder directly in the terminal run

```sh
unzip data.zip
```


## Objectives 

At the end of this repo you should
* know how to use scikit-learn to train a linear regression model.
* have an understanding of the usage and limitations of linear regression.
* know how to use the statsmodels library for OLS.
