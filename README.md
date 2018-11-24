# Cookiecutter: DataScience template

_A flexible project structure for doing and sharing data science work._


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, at the parent directory, run:
------------
```
    cookiecutter https://github.com/chris-chua/cookiecutter-datascience
```


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
folder_name
├── data (added to .gitignore)
│   ├── processed           <- The final, canonical data sets for modeling.
│   └── raw                 <- The original, immutable data dump.
│
├── analysis                <- Jupyter notebooks, Excel, etc. 
|   ├── 1-dataprep.ipynb    <- Generates interim and processed data.
|   └── 2-eda.ipynb         <- Exploratory data analysis.             
│
└── reports                 <- Generated analysis as HTML, PDF, LaTeX, etc.

(optional folders)
├── README.md               <- The top-level README for developers using this project.
|
├── requirements.txt        <- The requirements file for reproducing the analysis environment, 
|                              e.g. generated with `pip freeze > requirements.txt`
|
├── references              <- Data dictionaries, manuals, and all other explanatory materials.
│
├── docs                    <- Documentation for any code that is part of your deliverables.
|                              Use a tool such as Sphinx or roxygen2 to generate 
|                              documentation from comments in your code so you don't have
|                              to maintain it manually.
├── env*                    <- Location for virtualenv's, database info, etc.
├── models*                 <- Trained and serialized models, model predictions, or model summaries
│
└── src                     <- Custom source code module for import into this project.
    ├── __init__.py         <- Makes src a Python module
    ├── data                <- Scripts to download or generate data
    │   └── make_dataset.py
    ├── features            <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    ├── models              <- Scripts to train models and then use trained models to make
    │   │                   predictions
    │   ├── train_model.py
    │   └── predict.py
    └── visualization       <- Scripts to create exploratory and results oriented figures
        └── visualize.py
        
Note: directories with asterisks* need to be listed in .gitignore to be excluded from source control.
```


### Helpful Resources
------------
- [Cookiecutter Github repo](https://github.com/audreyr/cookiecutter)
- [Cookiecutter documentation](https://cookiecutter.readthedocs.io)
- [DrivenData's Cookiecutter Data Science template](https://github.com/drivendata/cookiecutter-data-science)