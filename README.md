# Notebooks

## Setup

To get started, open a terminal in the cloned repository:

```
virtualenv -p /usr/bin/python3 env
source env/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name notebooks --display-name "Python 3.7 for all notebooks"
```

## Running the notebook server

To start the notebook server run the command `jupyter notebook` and a browser should open.

## Making changes

If you add additional dependencies to the project, you can update the 
requirements file with the following command:

```
pip freeze > requirements.txt
```
