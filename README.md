[![Shipping files](https://github.com/neuefische/ds-linear-regression/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-linear-regression/actions/workflows/workflow-02.yml)
# Linear Regression

This repository will cover various topics related to linear regression:
* Simple and multiple linear regression with scikit-learn
* Simple and multiple linear regression with statsmodels
* Limitations of Linear Regression
* Interacting with Categorical Variables

## Set up your Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the linear regression notebooks.


### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

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
