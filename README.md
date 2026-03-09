# AI Programming Foundations Project

This project presents a complete, reproducible data workflow using Python in the form of Jupyter Notebook. Notebook contains all the necessary logic for cleaning and exploring data in a form of easy to use functions. Dataset `Titanic - Machine Learning from Disaster` (`train.csv`) is already included in the repository, it was collected from Kaggle ([source](https://www.kaggle.com/c/titanic/data?select=train.csv))

## Setup

To be able to run the project:
- install Python 3.12 (follow instructions [here](https://www.python.org/downloads/) or [here](https://www.anaconda.com/docs/getting-started/miniconda/install))
- create virtual environment: `python -m venv .venv`
- activate virtual environment: `source .venv/bin/activate` (macOS/Linux) or `.venv\Scripts\activate` (Windows)
- install required dependencies: `pip install -r requirements.txt`

## How to run

Once virtual environment is active:
- run command: `jupyter notebook`
- Jupyter should open in a new window of the default browser (if not follow the link from the output of previous command)
- click `data_workflow.ipynb` to open notebook
- to run all cells click: `Run` -> `Run All Cells`
