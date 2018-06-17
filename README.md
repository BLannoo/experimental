# Experimental

This project is a set of Jupyter notebooks I wrote to teach myself Jupyter in a hands-on way

## Setup python virtual environment

* Install python

```[sudo] brew install python```

* Install virtual environment

```pip install virtualenv```

* Create a folder to store your python virtual environments

```
cd
mkdir .virtualenvironment
```

* Create a virtual python environment

```
cd .virtualenvironment
virtualenv -p python3 experimental
```

## Install the required packages in your virtual environment

* Go to the root folder of your clone of the github repository

* Activate your virtual environment

```
source startVirtualenv.sh
```

* Install pyton requirements

```
pip install -r requirements.txt
```

* If you want to stop working in this virtual environment

```
deactivate
```

## Start your Jupyter notebook

```
source startVirtualenv.sh
jupyter notebook
```

* If you didn't get redirected automatically, browse to http://localhost:8889/tree to see your notebooks
* Open the EightQueensProblem.ipynb notebook
* Run all cells: Cell -> Run All
